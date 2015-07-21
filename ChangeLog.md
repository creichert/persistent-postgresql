## 2.1.5

* Allow timestamp value in database to be serialized (presumes UTC timezone) [Yesod #391](https://github.com/yesodweb/persistent/issues/391)

## 2.1.4

* Treat unknown extension types as PersistDbSpecific values [#385](https://github.com/yesodweb/persistent/pull/385)

## 2.1.3

* Added a `Show` instance for `PostgresConf`.
* `createPostgresqlPoolModified` added, see [relevant mailing list discussion](https://groups.google.com/d/msg/yesodweb/qUXrEN_swEo/O0pFwqwQIdcJ)

## 2.1.2.1

Documentation typo fix

## 2.1.1

Added `FromJSON` instance for `PostgresConf`.
