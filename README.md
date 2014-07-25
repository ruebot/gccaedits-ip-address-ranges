# @gccaedits IP address ranges

### Description

This repository contains the configurations for the IP ranges used for [@gccaedits](http://twitter.com/gccaedits), and is the new home of the [Gist](https://gist.github.com/ruebot/605426d052168156ba37) file used for community contributions.

The original set of IP address came from [Wikipedia](https://en.wikipedia.org/wiki/Wikipedia:Blocking_IP_addresses).

`gccaedits.json` is part of a larger [config](https://github.com/edsu/anon/blob/master/config.json.template) file for [anon](https://github.com/edsu/anon), the software behind [@gccaedits](http://twitter.com/gccaedits).

### Contributing

Know of any IP address ranges that should be included? You have a couple of options to contribute. If you're familiar with Github and the Pull Request process, have at it! If you're not familiar with that process, please create a [New Issue](https://github.com/ruebot/gccaedits-ip-address-ranges/issues/new), and we'll work through the getting your contirbutions included that way.

When you are contributing IP address ranges, please provide a source and/or documentation. For instance, including a stable uri to the source in the commit message. Additionally, it is very helpful if each pull request containins only an addition or modification to a single agency, and please check to make sure your additions are valid. For example, `python -m json.tool` or `:%!python -m json.tool` in Vim.

No need to contribute RCMP IP ranges, there is already an [rcmp_edits](https://twitter.com/rcmp_edits).
### Sources

Sources used for information on IP ranges came from:

* [Wikipedia](https://en.wikipedia.org/wiki/Wikipedia:Blocking_IP_addresse)
* [Hurricane Electric](http://bgp.he.net/)
* [ARIN](http://whois.arin.net/ui)

### License

Public Domain
