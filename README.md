## Flags

Flags collected from [Flagpedia](http://flagpedia.net/) as part of [making isitchristmas.com](https://konklone.com/post/isitchristmas-dot-com-2012).

The `mini` versions of each flag ([example](https://github.com/isitchristmas/flags/blob/master/AD/mini.png)) are what get used over in the [isitchristmas/web](https://github.com/isitchristmas/web) repository that is deployed to the [actual website](https://isitchristmas.com).

### Using them

This repository uses Github Pages, so you can download each flag using the country code and the size you want.

A large Irish flag:

> [http://isitchristmas.io/flags/flags/IE/big.png](http://isitchristmas.io/flags/flags/IE/big.png)

Sizes:

* `mini` - height of 20px
* `normal` - height of 275px
* `big` - height of 800px
* `ultra` - height of 1280px

Flags come in different aspect ratios, so the width can vary. Check out [this JSON snippet](https://github.com/isitchristmas/web/blob/master/public/js/christmas.js#L237) if you want to grab pre-extracted dimensions.

**Note**: This does not have every flag in isitchristmas.com -- only flags of sovereign nations. There are some territories and other flags that were gathered separately. This only (currently) includes flags from Flagpedia.

Contributions of other flags welcome!

### Crawling/discovering flag URLs

You can use the [Github Repo Contents API](http://developer.github.com/v3/repos/contents/) to get a quick JSON view of each directory in the repository.

To get a list of all flags, visit:

> [https://api.github.com/repos/isitchristmas/flags/contents/flags/?ref=gh-pages](https://api.github.com/repos/isitchristmas/flags/contents/flags/?ref=gh-pages)


### Scoche of code

There's also a [hacky Node script](https://github.com/isitchristmas/flags/blob/master/flagpedia.js) I used to scrape Flagpedia.

You can also use it with `imagemagick` to calculate the widths of each flag, if you want. But I [already did that here](https://github.com/isitchristmas/web/blob/master/public/js/christmas.js#L237).

### License

Er, these are national flags, I'm just gonna assume they're fully public domain, hopefully that's true, have fun.