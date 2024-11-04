# experience-flows

## Example Configuration
```
{
  "version": "1.0.1",
  "branding": {
    "companyLogoUrl": "https://assets.pingone.com/ux/ui-library/5.0.2/images/logo-pingidentity.png",
    "companyName": "Ping Identity",
    "showLogo": true,
    "theme": {
      "buttonBackgroundColor": "#277ba5",
      "buttonTextColor": "#ffffff",
      "cardBorderRadius": "0",
      "errorColor": "#a31300",
      "fontfamily": "'Montserrat', 'sans-serif'",
      "formBackgroundColor": "#ffffff",
      "formControlBorderRadius": "0",
      "formWidth": "460",
      "headingColor": "#3d454d",
      "linkButtonColor": "#277ba5",
      "primaryTextColor": "#3d454d"
    }
  },
  "mfa": {
    "enabled": false
  },
  "risk": {
    "id": "",
    "enabled": false
  },
  "selfservice": {
    "enableAccountRecovery": true,
    "enableRegistration": true
  },
  "social": {
    "enabled": false,
    "providers": {
      "facebook": false,
      "github": false,
      "google": false,
      "microsoft": false
    }
  },
  "webauthn": {
    "origin": "https://experience-builder-dev.glitch.me",
    "rpid": "experience-builder-dev.glitch.me"
  }
}
```