Publish your streamsync extension using this repo

1. [create your extension following the tutorial](https://www.streamsync.cloud/custom-components.html)
2. delete existing files in ``src/streamsync_bubblemessage`` folder
2. copy generated files into ``src/streamsync_bubblemessage``
3. rename ``streamsync_bubblemessage`` occurrences to ``streamsync_{{yourname}}``

    * in the repo name
    * in the src packages
    * in the pyproject.toml manifest

4. write your readme
5. publish the extension to pypi

```bash
poetry build
poetry publish
```

6. [share your extension on streamsync](https://github.com/streamsync-cloud/streamsync/discussions)
---

## streamsync_bubblemessage

This extension adds components to a [streamsync application](https://www.streamsync.cloud/) :

* Bubble Message
* Bubble Message (Advanced)

![demo](https://github.com/FabienArcellier/streamsync_bubblemessage/raw/master/img.png)

### Installation

```bash
pip install streamsync_bubblemessage
```
