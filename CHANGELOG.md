# Change log

## 0.2.2 (2018-03-28)

-  [Fix [#14](https://github.com/palkan/isolator/issues/14)] Always use default value for threshold. ([@palkan][])

    Previously, in multi-threaded env the default value were missing (and led to `KeyError`).

## 0.2.1 (2018-02-24)

- [PR [#10](https://github.com/palkan/isolator/pull/10)] Add `sucker_punch` adapter. ([@alexshgov][])
- [PR [#9](https://github.com/palkan/isolator/pull/9)] Add `resque scheduler` background job adapter. ([@dsalahutdinov][])

## 0.2.0 (2018-02-22)

- [PR [#8](https://github.com/palkan/isolator/pull/8)] Add resque background job adapter. ([@dsalahutdinov][])

## 0.1.1 (2018-02-21)

- Update `sniffer` required mininum version. ([@palkan][])

## 0.1.0 (2018-02-19)

- Add `test_after_commit` patch. ([@palkan][])

- [PR [#7](https://github.com/palkan/isolator/pull/7)] Add WebMock adapter. ([@palkan][])

- Add `ignore_if` modifier to adapter. ([@palkan][])

- [PR [#5](https://github.com/palkan/isolator/pull/5)] Add `mail` adapter. ([@alexshgov][])

- Initial version. ([@palkan][], [@TheSmartnik][], [@alexshgov][])

[@palkan]: https://github.com/palkan
[@alexshgov]: https://github.com/alexshgov
[@TheSmartnik]: https://github.com/TheSmartnik
[@dsalahutdinov]: https://github.com/dsalahutdinov
