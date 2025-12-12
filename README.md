<div align="center">
  <img
    src="https://avatars.githubusercontent.com/u/56705483"
    alt="Hoppscotch"
    height="64"
  />
  <h3>
    <b>
      Hoppscotch
    </b>
  </h3>
  <b>
    Open Source API Development Ecosystem
  </b>
  <p>
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./packages/hoppscotch-common/public/images/banner-dark.png">
      <source media="(prefers-color-scheme: light)" srcset="./packages/hoppscotch-common/public/images/banner-light.png">
      <img alt="Hoppscotch" src="./packages/hoppscotch-common/public/images/banner-dark.png">
    </picture>
  </p>
</div>

### **Features**

❤️ **Lightweight:** Crafted with minimalistic UI design.

⚡️ **Fast:** Send requests and get responses in real time.

🗄️ **HTTP Methods:** Request methods define the type of action requested to be performed.

- `GET` - Requests retrieve resource information
- `POST` - The server creates a new entry in a database
- `PUT` - Updates an existing resource
- `PATCH` - Very similar to `PUT` but makes a partial update on a resource
- `DELETE` - Deletes resource or related component
- `HEAD` - Retrieve response headers identical to those of a GET request, but without the response body.
- `CONNECT` - Establishes a tunnel to the server identified by the target resource
- `OPTIONS` - Describe the communication options for the target resource
- `TRACE` - Performs a message loop-back test along the path to the target resource
- `<custom>` - Some APIs use custom request methods such as `LIST`.

🌈 **Theming:** Customizable combinations for background, foreground, and accent colors.

- Choose a theme: System preference, Light, Dark, and Black
- Choose accent colors: Green, Teal, Blue, Indigo, Purple, Yellow, Orange, Red, and Pink
- Distraction-free Zen mode

🔥 **PWA:** Install as a [Progressive Web App](https://web.dev/progressive-web-apps).

- Instant loading with Service Workers
- Offline support
- Low RAM/memory and CPU usage
- Add to Home Screen
- Desktop PWA

🚀 **Request:** Retrieve response from endpoint instantly.

1. Choose `method`
2. Enter `URL`
3. Send

- Copy/share public "Share URL"
- Generate/copy request code snippets for 10+ languages and frameworks
- Import `cURL`
- Label requests

🔌 **WebSocket:** Establish full-duplex communication channels over a single TCP connection.

📡 **Server-Sent Events:** Receive a stream of updates from a server over an HTTP connection without resorting to polling.

🌩 **Socket.IO:** Send and Receive data with the SocketIO server.

🦟 **MQTT:** Subscribe and Publish to topics of an MQTT Broker.

🔮 **GraphQL:** GraphQL is a query language for APIs and a runtime for fulfilling queries with existing data.

- Set endpoint and get schema
- Multi-column docs
- Set custom request headers
- Query schema
- Get query response

🔐 **Authorization:** Allows to identify the end-user.

- None
- Basic
- Bearer Token
- OAuth 2.0
- OIDC Access Token/PKCE

📢 **Headers:** Describes the format the body of the request is being sent in.

📫 **Parameters:** Use request parameters to set varying parts in simulated requests.

📃 **Request Body:** Used to send and receive data via the REST API.

- Set `Content Type`
- FormData, JSON, and many more
- Toggle between key-value and RAW input parameter list

📮 **Response:** Contains the status line, headers, and the message/response body.

- Copy the response to the clipboard
- Download the response as a file
- View response headers
- View raw and preview HTML, image, JSON, and XML responses

⏰ **History:** Request entries can be synced between cloud and local session storage.

📁 **Collections:** Keep API requests organized with collections and folders. Reuse them with a single click.

- Unlimited collections, folders, and requests
- Nested folders
- Export and import as a file or GitHub gist

📜 **Pre-Request Scripts:** Snippets of code associated with a request that is executed before the request is sent.

- Set environment variables
- Include timestamp in the request headers
- Send a random alphanumeric string in the URL parameters
- Any JavaScript functions

👨‍👩‍👧‍👦 **Teams:** Collaborate across your teams to design, develop, and test APIs faster.

- Create unlimited teams
- Create unlimited shared collections
- Create unlimited team members
- Role-based access control
- Cloud sync
- Multiple devices

👥 **Workspaces:** Organize personal and team collections environments into workspaces. Easily switch between workspaces to manage multiple projects.

- Create unlimited workspaces
- Switch between personal and team workspaces

⌨️ **Keyboard Shortcuts:** Optimized for efficiency.

> **[Read documentation on Keyboard Shortcuts](https://docs.hoppscotch.io/documentation/features/shortcuts)**

🌐 **Proxy:** Enable Proxy Mode from Settings to access blocked APIs.

- Hides IP address
- Fixes [`CORS`](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) (Cross-Origin Resource Sharing) issues
- Access APIs served in non-HTTPS (`http://`) endpoints
- Uses Proxy URL

**Sign in with:**

- GitHub
- Google
- Microsoft
- Email
- SSO (Single Sign-On)[^EE]

**🔄 Synchronize data:** Handoff to continue tasks on other devices.

- Workspaces
- History
- Collections
- Environments
- Settings

✅ **Post-Request Tests:** Write tests associated with a request that is executed after the request's response.

- Check the status code as an integer
- Filter response headers
- Parse the response data
- Set environment variables
- Write JavaScript code

🌱 **Environments:** Environment variables allows to store and reuse values in requests and scripts.

- Unlimited environments and variables
- Initialize through the pre-request script
- Export as / import from GitHub gist

<details>
  <summary><i>Use-cases</i></summary>

---

- By storing a value in a variable, you can reference it throughout your request section
- If you need to update the value, you only have to change it in one place
- Using variables increases your ability to work efficiently and minimizes the likelihood of error

---

</details>

🚚 **Bulk Edit:** Edit key-value pairs in bulk.

- Entries are separated by newline
- Keys and values are separated by `:`
- Prepend `#` to any row you want to add but keep disabled

🎛️ **Admin dashboard:** Manage your team and invite members.

- Insights
- Manage users
- Manage teams

📦 **Add-ons:** Official add-ons for hoppscotch.

- **[Hoppscotch CLI](https://github.com/RubisetCie/hoppscotch/tree/main/packages/hoppscotch-cli)** - Command-line interface for Hoppscotch.
- **[Proxy](https://github.com/RubisetCie/proxyscotch)** - A simple proxy server created for Hoppscotch.
- **[Browser Extensions](https://github.com/RubisetCie/hoppscotch-extension)** - Browser extensions that enhance your Hoppscotch experience.

  [![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_16x16.png) **Firefox**](https://addons.mozilla.org/en-US/firefox/addon/hoppscotch) &nbsp;|&nbsp; [![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_16x16.png) **Chrome**](https://chrome.google.com/webstore/detail/hoppscotch-extension-for-c/amknoiejhlmhancpahfcfcfhllgkpbld)

  > **Extensions fix `CORS` issues.**

_Add-ons are developed and maintained under **[Hoppscotch Organization](https://github.com/RubisetCie)**._

**For a complete list of features, please read the [documentation](https://docs.hoppscotch.io).**

## Usage

1. Provide your API endpoint in the URL field
2. Click "Send" to simulate the request
3. View the response

## Authors

This project owes its existence to the collective efforts of all the [original contributors](https://github.com/RubisetCie/hoppscotch/graphs/contributors).

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) — see the [`LICENSE`](LICENSE) file for details.

[^EE]: Enterprise edition feature. [Learn more](https://docs.hoppscotch.io/documentation/self-host/getting-started).
