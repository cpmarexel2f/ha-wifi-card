# Changelog

## 1.4.1

### Changes
- Lighter blue for the WiFi logo and the QR code background; the QR code also scans more reliably at small sizes.

## 1.4.0

### Changes
- The QR code background now uses the same blue as the WiFi logo, like the Wero card does with its yellow.

## 1.3.1

### Changes
- New WiFi logo in the card header: white waves on a blue rounded square.

## 1.3.0

### What's new
- WiFi logo in the card header, like the Wero card. Turn it off with `logo: false` or from the visual editor to get the plain `mdi:wifi` icon back.

## 1.2.0

### What's new
- Visual editor for the card: title, SSID, password, security, QR code size and language, no YAML needed. Labels in English and French.
- WPA3 (`SAE`) security available in the editor.
- Open networks (`security: nopass`): the password is no longer required and the card shows "Open network" instead.
- Card preview in the card picker.

### Maintenance
- Releases are now published automatically from this changelog when the version is bumped.

## 1.1.0

### What's new
- Click or tap the QR code to show it full screen (click again, click outside or press Escape to close), keyboard accessible with Enter or Space.
- Default `qr_size` is now 200 px, quiet zone included, like the Wero card.

## 1.0.0

First public release.

### What's new
- WiFi QR code generated in pure JavaScript, no dependencies, no CDN.
- Password hidden by default, revealable with one click.
- Language detected from Home Assistant (English / French).
- Light and dark theme compatible, installable via HACS.
