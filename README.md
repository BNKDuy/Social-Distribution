Social Distribution
===================================
A distributed social network built with Django, designed for seamless communication and content sharing across independent servers (nodes). This platform is part of a federated ecosystem. Each "node" acts as an independent social media server, but through a common REST API specification, users on Server A can follow, like, and comment on posts from users on Server B.
  
**Team Members**:
- Duy Bui Nguyen Khuong
- Tiana Huynh
- Vinu Aravindh Ramesh
- Vinay Joshi
- Son Tran
- Aykhan Teymurlu

## Features

- **Distributed Architecture**: Supports internode communication via standardized API endpoints.
- **Dual Authentication**:
  - **Frontend to Backend**: JSON Web Tokens (JWT).
  - **Internode (Server-to-Server)**: HTTP Basic Auth over HTTPS.
- **RESTful API**: A fully documented API that allows integration with other compatible social distribution nodes.
- **Content Management**: Support for posts, comments, likes, and friend requests across the network.

## Tech Stack
- **Backend**: Django
- **Database**: PostgreSQL
- **Authentication**: JWT & HTTP Basic Auth
- **API Specification**: REST

## License

GNU General Public License version 3

## Copyright

The authors claiming copyright, if they wish to be known, can list their names here...

* Vinay Joshi
* Duy Bui Nguyen Khuong
* Tiana Huynh
* Son Tran
* Vinu Aravindh Ramesh
* Aykhan Teymurlu
