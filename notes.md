# Android UI Notes

### textAllCaps
- attribute used to control whether text is shown in ALL CAPS.
- `android:textAllCaps="true"` → TEXT IS CAPITALIZED
- `android:textAllCaps="false"` → Text appears as written
- Default: `true` for Buttons, `false` for TextView

---

### xmlns:app
- Namespace used to access custom attributes.
- Must be declared in the root layout:
  ```xml
  xmlns:app="http://schemas.android.com/apk/res-auto"
