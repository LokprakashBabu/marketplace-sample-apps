Feature | Description
------- | -----------
Data Storage | To enable the development of Key/Value db needed apps, we provide a data store for apps to set (store) and get (retrieve) data. Also, data can be deleted when it is no longer required.
Request API | You should use the Request API to avoid exposing sensitive information, such as API keys or user credentials, when you make HTTP requests to third-party domains as agents will be able to inspect these values in a browser and access them. The other benefit is Cross-Origin Resource Sharing (CORS) support as requests are routed through a proxy.
Instace API | A single app can be present in multiple locations on the same page. In addition, a location may open up one or more modals. The locations and modals can be thought of as separate instances of the app and can be resized, closed, and communicate with each other. The app framework provides instance APIs to enable these use cases.
OAuth 2 | You can use the OAuth 2 protocol to authorize an app to access resources from third-party applications. This is done by using an access token obtained from the third-party when the app is installed.
