* [#9316](https://github.com/rubocop-hq/rubocop/issues/9316): Fix `Style/EmptyLiteral` registering wrong offense when using a numbered block for Hash.new, i.e. `Hash.new { _1[_2] = [] }`. ([@agargiulo][])