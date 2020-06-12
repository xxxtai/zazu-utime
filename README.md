[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/puyt/zazu-utime)


this repo is forked from puyt/zazu-utime, the result of puyt/zazu-utime always displayed first. Therefore, I added the prifix 'utime' on the basis of previous.

## Zazu-utime

A simple timestamp plugin for [Zazu](http://zazuapp.org/), inspired by this [Chrome extension](https://chrome.google.com/webstore/detail/kpcibgnngaaabebmcabmkocdokepdaki).


## Usage

Open Zazu and type a timestamp or human-readable date, the plugin will try and translate most of it.

Examples:
- `utimenow`
- `utime now`
- `utime today`
- `utime1487718000`
- `utime2020-06-13 00:00:00`

For more examples see https://sugarjs.com/dates/#/Parsing


## Installing

Add `xxxtai/zazu-utime` inside of `plugins` block of your  `~/.zazurc.json` file.

~~~ json
{
  "plugins": [
      "xxxtai/zazu-utime"
  ]
}
~~~

### Variables
- `timestampUnit`: seconds or milliseconds
- `outputFormat`: see https://sugarjs.com/dates/#/Formatting for all possible options

~~~ json
{
  "plugins": [
    {
        "name": "xxxtai/zazu-utime",
        "variables": {
            "timestampUnit": "milliseconds",
            "outputFormat": "{yyyy}-{MM}-{dd} {HH}:{mm}:{s}"
        }
    }
  ]
}
~~~


## Screenshots
![example1](./assets/20200612222759.jpg)
![example2](./assets/20200612222847.jpg)
![example3](./assets/20200612222948.jpg)
![example4](./assets/20200612223005.jpg)


## Acknowledgments
Most of the plugin it's :muscle: is coming from [Sugarjs](https://sugarjs.com/)


## See also
- [`tinytacoteam/zazu`](http://github.com/tinytacoteam/zazu)

## License

[MIT](LICENSE.md)
