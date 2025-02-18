# capacitor-zip-android

Unzip files on android.

## Install

```bash
npm install @elvis-ibrahimi/capacitor-zip-android
npx cap sync
```

## Android permissions
Make sure to add the following permissions in the application android manifest.xml
```xml
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE"/>
```

## API

<docgen-index>

* [`unzip(...)`](#unzip)
* [Interfaces](#interfaces)

</docgen-index>

<docgen-api>
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->

### unzip(...)

```typescript
unzip(options: UnzipOptions) => Promise<UnzipResult>
```

| Param         | Type                                                  |
| ------------- | ----------------------------------------------------- |
| **`options`** | <code><a href="#unzipoptions">UnzipOptions</a></code> |

**Returns:** <code>Promise&lt;<a href="#unzipresult">UnzipResult</a>&gt;</code>

--------------------


### Interfaces


#### UnzipResult

| Prop          | Type                |
| ------------- | ------------------- |
| **`message`** | <code>string</code> |
| **`uri`**     | <code>string</code> |


#### UnzipOptions

| Prop              | Type                |
| ----------------- | ------------------- |
| **`source`**      | <code>string</code> |
| **`destination`** | <code>string</code> |
| **`password`**    | <code>string</code> |

</docgen-api>
