# smartUp Relay Privacy Policy

Last updated: November 9, 2026

smartUp Relay is a browser extension for user-configured mouse gestures, drag actions, tab management, and related browser actions. This policy describes the information handled by the extension and its optional features.

## Information processed by the extension

### Extension settings and notes

Gesture definitions, action settings, and other preferences are stored in the browser's extension storage. Depending on the browser and its available storage APIs, settings may use browser sync storage or local extension storage. Mini-app notes and related user-created content are stored in local extension IndexedDB. The extension does not send these settings or notes to the developer's servers.

### Webpage information used for requested actions

To carry out an action that the user configures and invokes, the extension may read the current tab's URL or title, a selected link or text, or an image URL. This information is processed to perform the requested action, such as opening a link, copying selected content, creating a bookmark, or navigating between tabs. The extension does not maintain a browsing-history profile or send browsing history to the developer.

## Optional features and external requests

Some optional features make network requests. The recipient of a request can receive ordinary connection information, such as the device's IP address and standard HTTP request metadata. The extension does not attach an account identifier to these requests.

- **Short URL action:** When the user invokes this feature, the current page URL and the user-configured keyword are sent to the configured URL-shortening service. The default service is `url.zimoapps.com`; users may configure another service. The service processes the URL to return a shortened link and handles it under its own privacy terms.
- **RSS reader:** The extension requests the feed URL configured by the user and reads the returned feed to display its entries. The feed provider receives the request in the same way as a normal web request.
- **Image copying:** When the user invokes the image-copy action, the extension requests the selected image from its source so it can place the image on the clipboard. The image host receives that request.
- **Homepage background:** If the user enables the related homepage feature, the extension requests public background-image information from Bing and may fetch the selected image from its image host.
- **Optional content mini-apps:** Some mini-apps request public content from their configured or built-in providers, including `www.poxiao.com`. These requests retrieve content for display. A mini-app may also request a URL selected by the user.
- **Donation and sponsor configuration:** The extension requests configuration from `apis.zimoapps.com` to determine whether donation or sponsor information is available. This request does not include the user's page URL or extension settings. If a sponsor page is displayed or opened, that third-party site may collect information according to its own privacy policy.

User-facing actions such as shortening a URL, loading an RSS feed, or copying an image are initiated by the user. The donation and sponsor configuration request runs when the extension's background service starts. The extension does not send browsing information to build advertising profiles or sell user data.

## Sharing and retention

Information is shared with an external service only as described above and when the relevant feature is used or enabled. The extension developer does not receive a copy of locally stored settings or notes. Data retained by a third-party provider is governed by that provider's terms and privacy policy. Local extension data can be removed by clearing the extension's data or uninstalling the extension; browser-synced settings are also subject to the browser account's sync and deletion controls.

## Security

Network requests made by the extension use HTTPS where supported by the configured service. Users should avoid sending sensitive URLs to a third-party URL-shortening service unless they trust that service.

## Children's privacy

smartUp Relay is a general-purpose browser productivity extension and is not designed to collect personal information from children.

## Changes to this policy

This policy may be updated when the extension's functionality or data practices change. The current version will be published at this URL. Material changes will be reflected in the extension's store disclosures where required.

## Contact

For privacy questions or requests, contact `germxu@gmail.com` or open an issue at [github.com/Germxu/smartup-relay/issues](https://github.com/Germxu/smartup-relay/issues).

---

# smartUp Relay 隐私权政策

最后更新：2026 年 11 月 9 日

smartUp Relay 是一款浏览器扩展，用于用户自定义的鼠标手势、拖拽操作、标签页管理及相关浏览器操作。本政策说明扩展处理的信息以及可选功能涉及的数据流。

## 扩展处理的信息

### 扩展设置和笔记

手势定义、动作设置及其他偏好保存在浏览器扩展存储中。根据浏览器及其存储 API，设置可能保存在浏览器同步存储或本地扩展存储中。迷你应用笔记及相关用户创建的内容保存在本地扩展 IndexedDB 中。扩展不会将这些设置或笔记发送到开发者服务器。

### 为执行用户请求的操作而处理的网页信息

为了执行用户配置并主动触发的操作，扩展可能读取当前标签页的网址或标题、选中的链接或文本、图片网址等信息。这些信息用于完成相应操作，例如打开链接、复制选中内容、创建书签或切换标签页。扩展不会建立浏览历史画像，也不会将浏览历史发送给开发者。

## 可选功能和外部请求

部分可选功能会发起网络请求。请求接收方可能获得设备 IP 地址及标准 HTTP 请求元数据等常规连接信息。扩展不会在这些请求中附加用户账户标识。

- **短网址动作：** 用户触发此功能时，当前页面 URL 和用户设置的关键词会发送到所配置的短网址服务。默认服务为 `url.zimoapps.com`，用户也可以设置其他服务。服务会处理该 URL 并返回短网址，其处理方式受该服务自身的隐私条款约束。
- **RSS 阅读器：** 扩展请求用户配置的 RSS feed 地址，并读取返回内容以显示订阅条目。Feed 服务会像处理普通网页请求一样收到该请求。
- **复制图片：** 用户触发图片复制动作时，扩展会从图片来源请求所选图片，以便将图片写入剪贴板。图片托管方会收到该请求。
- **主页背景：** 用户启用相关主页功能后，扩展会向 Bing 请求公开的背景图片信息，并可能从图片托管方获取所选图片。
- **可选内容迷你应用：** 部分迷你应用会从配置或内置的内容提供方请求公开内容，包括 `www.poxiao.com`。这些请求用于获取并显示内容；迷你应用也可能请求用户选择的网址。
- **捐赠及赞助配置：** 扩展会向 `apis.zimoapps.com` 请求配置，以判断是否提供捐赠或赞助信息。该请求不包含用户当前页面 URL 或扩展设置。如果显示或打开赞助方页面，第三方网站可能根据其自身隐私政策收集信息。

短网址、RSS 和复制图片等面向用户的操作由用户主动触发。捐赠及赞助配置请求会在扩展后台启动时发起。扩展不会发送浏览信息以建立广告画像，也不会出售用户数据。

## 信息共享和保留

仅在上述功能被使用或启用时，扩展才会按说明向相关外部服务发送信息。扩展开发者不会收到本地保存的设置或笔记副本。第三方服务保留数据的方式受其自身条款和隐私政策约束。用户可以清除扩展数据或卸载扩展来删除本地扩展数据；浏览器同步的设置也受浏览器账户的同步和删除控制管理。

## 安全

扩展在服务支持的情况下使用 HTTPS 发起网络请求。向第三方短网址服务提交网址前，请确认信任该服务，避免提交敏感网址。

## 儿童隐私

smartUp Relay 是面向大众的浏览器效率工具，并非用于收集儿童个人信息的产品。

## 政策变更

当扩展功能或数据处理方式发生变化时，本政策可能随之更新。当前版本会发布在此页面；如有需要，商店中的相关披露信息也会同步更新。

## 联系方式

如有隐私相关问题或请求，请联系 `germxu@gmail.com`，或在 [github.com/Germxu/smartup-relay/issues](https://github.com/Germxu/smartup-relay/issues) 提交问题。
