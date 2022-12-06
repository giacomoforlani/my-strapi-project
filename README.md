## How to reproduce the bug

- run `yarn`
- run `yarn develop`
- go to page http://localhost:1337/admin/content-manager/collectionType/api::page.page/1
- login use following credentials:
  - email: foo.bar@gmail.com
  - password: FooBar123!
- to reproduce the bug, perform one of this actions inside the dynamic zone:
  - move up/down any component
  - delete any component
