# tensorflow-lite-conan

Conan recipe for TFLite for use with [Edgerunner](https://github.com/neuralize-ai/edgerunner).
Clone this repo and run;

```bash
conan create all/conanfile.py --version <version>
```

from the root directory of the project to make it
available locally before trying to use Edgerunner with TFLite support. For a list of versions see [config.yml](config.yml).

I will try to make this available on Conan Center shortly.
