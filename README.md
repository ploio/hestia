# Hestia

[Packer][] is used to build some boxes.
See: https://atlas.hashicorp.com/portefaix

## Usage

* Install [Packer][].

* Setup your [Atlas][] configuration :

		$ export HESTIA_ATLAS_USERNAME="xxx"
		$ export HESTIA_ATLAS_TOKEN="xxx"

* Build boxes :

        $ make buid template=xxx

* Deploy to Atlas :

        $ make push template=xxx


## License

See [LICENSE][] for the complete license.


## Changelog

A changelog is available [here](ChangeLog.md).


## Contact

Nicolas Lamirault <nicolas.lamirault@gmail.com>


[LICENSE]: https://github.com/nlamirault/bento/blob/master/LICENSE

[Packer]: https://www.packer.io/
[Atlas]: https://atlas.hashicorp.com
