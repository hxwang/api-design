# api-design

## API
- [ref](http://maxivak.com/rest-vs-xml-rpc-vs-soap/)


  

### Design API
- Include version number
  - version your API from the outset, explicitly incorporating a version number into the URL (e.g., http://myapisite.com/api/widgets?version=1 or http://myapisite.com/api/widgets/v1) so that people can rely on version 1 working and can upgrade to any subsequent version when they’re ready to do so.

### REST v.s. RPC
- The main advantages of REST web services are:
  - Lightweight – not a lot of extra xml markup
  - Human Readable Results
  - Easy to build – no toolkits required
- SOAP also has some advantages:
  - Easy to consume – sometimes
  - Rigid – type checking, adheres to a contract
  - Development tools
- XML-PRC
  - Long story short: XML-RPC is simpler to learn and use, but SOAP is more powerful
