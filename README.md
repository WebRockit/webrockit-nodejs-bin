### webrockit-node-bin

This package fetches nodejs binaries and builds a nodejs package, staging the base path to /opt/nodejs.  The package webrockit-node-bin must exist on a webrockit poller node (Sensu client).

### To build

   - run ./buildme.sh

This will download the nodejs binary from the official distribution site, and re-package it into the /opt/nodejs path.  The final package is located under ./finalpkg/

### License
   webrockit-node-bin is released under the MIT license, and bundles other liberally licensed OSS components [License](LICENSE.txt)  
   [Third Party Software](third-party.txt)
