![Publish Status](https://github.com/ether/ep_kaput/workflows/Node.js%20Package/badge.svg) ![Backend Tests Status](https://github.com/ether/ep_kaput/workflows/Backend%20tests/badge.svg)

# Try to break Etherpad plugin system!

This plugin is designed to be malicious and if installed it's purpose is to crash your Etherpad instance and make it unavailable.

## Installation

```shell
npm install ep_kaput
```

or Use the Etherpad ``/admin`` interface.

## Testing

### Frontend

Visit http://whatever/tests/frontend/ to run the frontend tests.

### Backend

Type ``cd src && npm run test`` to run the backend tests.

## Copyright and License

Copyright © 2013–2021 John McLear <john@mclear.co.uk>

Licensed under the [Apache License, Version 2.0](LICENSE) (the "License"); you
may not use this file except in compliance with the License. You may obtain a
copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed
under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied. See the License for the
specific language governing permissions and limitations under the License.
