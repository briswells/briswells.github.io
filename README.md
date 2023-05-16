# Open Source maintenance portfolio

### Highlights

* **Setup Authentication between docker containers** [[1]](https://github.com/ChicoState/PantryNode/pull/180): Completed the intagrations between backend and frontend containers so they were both using the same JWT token method for authentication. This included updating the backend to set a token in local store when requested by the frontend, ensure the backend checked for expired tokens, and ensure the frontend authentication was setup to the token for authentication. [hardikpatil](https://github.com/hardikpatil) and [AbhinavReddy-Dev](https://github.com/AbhinavReddy-Dev) helped in an advisor role, but didn't commit any code.
* **Designed Schema for new DB and created Sequelize models** [[1]](https://github.com/ChicoState/PantryNode/commit/0813c50a91f1f0e921bf322530025e953053d432) [[2]](https://github.com/ChicoState/PantryNode/commit/464b440f6ed984e8f89c26dd15744a176d31b304): Due to the database being moved from a document based DB to a relation DB a new schema was needed. A new DB was created for PostgresSQL and Sequelize models were implemented in tpyescript to avoiud direct SQL use within the app. [Mmurtey](https://github.com/ChicoState/PantryNode/commits?author=MMurtey) assisted in an advisory capacity but no code was commited.

### Timeline

Unless otherwise stated all code commits where merged into main.

## Sprint 1

* [Created schema for scalable database in 3NF](https://github.com/ChicoState/PantryNode/commit/0813c50a91f1f0e921bf322530025e953053d432)
* [Created models for schema using sequelize](https://github.com/ChicoState/PantryNode/commit/464b440f6ed984e8f89c26dd15744a176d31b304)
* [Containerized Postgres and PSadmin](https://github.com/ChicoState/PantryNode/commit/cb5f892bd817c6bd290f497af3ea408396da99e4)
* Converted several of the previous routes to work with new DB [1](https://github.com/ChicoState/PantryNode/commit/250c320d0e1fcb694962957b908e86e36b389ca4)  [2](https://github.com/ChicoState/PantryNode/commits/main?before=1ff8f3f3c31d9a7cf0c4e59b2f937732cd9e5c55+175&branch=main&qualified_name=refs%2Fheads%2Fmain)
* [Updated local passport stratagy](https://github.com/ChicoState/PantryNode/commit/3b97252ac6a4067c295572286816177dbbb05b80) 

## Sprint 2

* [Pair Programmed with other members of Backend Team](https://github.com/ChicoState/PantryNode/commit/2aa5f1b6047c63a33aa167130105abfdaedab395) 
* [Implemented Git LFS](https://github.com/ChicoState/PantryNode/pull/80) PR Opened

## Sprint 3

* [Containerized React](https://github.com/ChicoState/PantryNode/pull/100)
* [Fixed Docker Package Issues](https://github.com/ChicoState/PantryNode/pull/149)
* [Created API route for feed](https://github.com/ChicoState/PantryNode/pull/153)
* [Created API route for stock](https://github.com/ChicoState/PantryNode/pull/154)
* [Allowed for hot app reloads on all systems](https://github.com/ChicoState/PantryNode/pull/158)
* [Updated login route to return json](https://github.com/ChicoState/PantryNode/pull/164)
* [Reviewed frontend updates PR](https://github.com/ChicoState/PantryNode/pull/140)

## Sprint 4
* [Fixed authentication stack between backend and frontend ](https://github.com/ChicoState/PantryNode/pull/180)
* [Assisted in implenting barcode feature 1](https://github.com/ChicoState/PantryNode/commit/d650acf4c6bfbac1f13dcc8b6d3318ca30ac1fdc)
* [Assisted in implenting barcode feature 2](https://github.com/ChicoState/PantryNode/commit/b93d5ff6672ab617c90751da39734c03bd5cc795)
* [Removed unneeded files from main](https://github.com/ChicoState/PantryNode/pull/209)
* [Reviewed PR for updating readme](https://github.com/ChicoState/PantryNode/pull/195)
* [Reviewed Link SKU to DB feature](https://github.com/ChicoState/PantryNode/pull/176)
* [Logged linter bug](https://github.com/ChicoState/PantryNode/issues/181)

## Sprint 5
* [Began working on single item lookup feature](https://github.com/ChicoState/PantryNode/tree/item-lookup) Unfinished Feature

## Notes

Generally assisted with communication between teams. Helped people get started on issues and answer questions over discord. 
