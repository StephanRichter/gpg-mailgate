# gpg-mailgate

gpg-mailgate is a content filter for Postfix that automatically encrypts unencrypted incoming email using PGP for select recipients.

For installation instructions, please refer to the included INSTALL file.

# Features
- Correctly displays attachments and general email content; currently will only display first part of multipart messages
- Public keys can be stored in a dedicated gpg-home-directory (see Note 1 in INSTALL)
- Encrypts matching incoming and outgoing mode
- Easy installation
- gpg-mailgate-web extension is a web interface allowing any user to upload PGP keys so that emails sent to them from your mail server will be encrypted (see gpg-mailgate-web directory for details)

This is forked from the original project at http://code.google.com/p/gpg-mailgate/
