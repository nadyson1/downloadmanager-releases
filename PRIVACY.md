# DownloadManager Edge Extension — Privacy Policy

**Last updated:** October 30, 2026

This privacy policy describes how the **DownloadManager** extension for Microsoft Edge processes information. The extension connects Microsoft Edge with the separately installed DownloadManager desktop application for Windows. The extension and desktop application currently provide their interfaces in Brazilian Portuguese.

## 1\. Information processed

The extension accesses a link address (URL) when you explicitly choose to send it to DownloadManager using the extension popup, the context menu on a link, or the configured modifier-click shortcut. A selected URL may itself contain information that identifies a person or provides access to a resource; review links before sending them.

The extension uses its local browser storage to save capture preferences, the chosen modifier-click shortcut, and recent connection or delivery status. It does **not** store submitted URLs in extension storage. A URL may be held briefly in memory to handle the request and prevent an immediate duplicate submission.

When modifier-click capture is enabled, the extension runs its packaged content script on supported HTTP and HTTPS pages to detect the user-selected link. It does not continuously record browsing history, keystrokes, or page content for analytics.

## 2\. How information is used

The extension sends the URL you select through Microsoft Edge **Native Messaging** to a locally installed component of the DownloadManager Windows application. The desktop application then presents the request for you to review. The extension does not independently download the file.

The extension does not send selected URLs to a web service operated by the extension developer. It does not use advertising networks, analytics services, or remotely hosted executable code.

## 3\. Sharing and the desktop application

The extension does not sell user information or share selected URLs with third-party advertising or analytics providers. Its intended transfer is from Microsoft Edge to the DownloadManager application **on the same Windows device**, following your explicit action.

The desktop application may subsequently contact the remote server associated with a download if you choose to proceed. Such network requests and any files or download history managed by the desktop application are separate from the extension's browser-local processing described here.

## 4\. Storage and retention

Extension settings and recent connection or delivery status remain in Microsoft Edge's local extension storage until changed, cleared, or removed through the browser's controls. URLs passed to the local messaging component are not retained in that extension storage. Temporary in-memory information is used for handling the selected request.

The extension developer does not maintain a remote database of links submitted through the extension.

## 5\. Your choices and controls

You can disable modifier-click capture or change the shortcut in the extension's options. You can choose not to submit any link, clear the extension's local data through Microsoft Edge, or uninstall the extension at any time. The desktop application can be managed separately through Windows.

## 6\. Security

Communication between the extension and the installed desktop component uses the browser's Native Messaging interface. The extension requests the permissions needed for its documented features. No system can guarantee absolute security; avoid sending URLs containing private access tokens unless necessary.

## 7\. Changes to this policy

This policy may be updated when the extension's behavior or data handling changes. The date at the top of this document will reflect the latest revision.

## 8\. Contact

For privacy questions, requests, or support, contact: **nadyson30@hotmail.com**.

