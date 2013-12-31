ArchiveClient
=========

an *archive.org* Ruby client

| Project                 |  Archive::Client    |
|------------------------ | ----------------- |
| gem name                |  archive-client   |
| license                 |  MIT              |
| moldiness               |  [![Maintainer Status](http://stillmaintained.com/wordtreefoundation/archive-client.png)](http://stillmaintained.com/wordtreefoundation/archive-client) |
| version                 |  [![Gem Version](https://badge.fury.io/rb/archive-client.png)](http://badge.fury.io/rb/archive-client) |
| dependencies            |  [![Dependency Status](https://gemnasium.com/wordtreefoundation/archive-client.png)](https://gemnasium.com/wordtreefoundation/archive-client) |
| code quality            |  [![Code Climate](https://codeclimate.com/github/wordtreefoundation/archive-client.png)](https://codeclimate.com/github/wordtreefoundation/archive-client) |
| continuous integration  |  [![Build Status](https://secure.travis-ci.org/wordtreefoundation/archive-client.png?branch=master)](https://travis-ci.org/wordtreefoundation/archive-client) |
| test coverage           |  [![Coverage Status](https://coveralls.io/repos/wordtreefoundation/archive-client/badge.png)](https://coveralls.io/r/wordtreefoundation/archive-client) |
| homepage                |  [https://github.com/wordtreefoundation/archive-client][homepage] |
| documentation           |  [http://rdoc.info/github/wordtreefoundation/archive-client/frames][documentation] |
| authors                 |  [Duane Johnson](https://coderbits.com/canadaduane) |
|                         |  [Peter Boling](https://coderbits.com/pboling) |
| Spread ~♡ⓛⓞⓥⓔ♡~      |  [![Endorse Duane](https://api.coderwall.com/canadaduane/endorsecount.png)](http://coderwall.com/canadaduane) |
|                         |  [![Endorse Peter](https://api.coderwall.com/pboling/endorsecount.png)](http://coderwall.com/pboling) |


Getting Started
---------------

```ruby
require 'archive-client'
```

Create an Archivist client:
```ruby
client = Archivist::Client.new
```

Search for the books you're interested in:
```ruby
books = client.search(:start_year => 1500, :end_year => 1510)
```

Download them:
```ruby
books.each do |book|
  puts book.download
end
```

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/wordtreefoundation/archive-client/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

