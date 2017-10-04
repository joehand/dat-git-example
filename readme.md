# Dat Git Example

You can use Dat alongside Git! Dat will store your data while Git stores your code.

In this example, we have an `index.html` as our code and cat pictures as our data. We check in our code and `dat.json` to Git while our data lives in a separate dat. You can view the [whole Dat](http://datproject.org/0961807e4d9bc4dbee2075a0fa78db499ae8a6bc2d613e17c35a7e49721d52e4) online.

### Using in your repository

* Use `dat create` to create a new dat for your data
* Add the `dat.json` file from your dat to git
* (optional) Add `.datdownload` to specify which files users will download by default.
* Add instructions, similar to below, on how to download data via dat.

## Example Usage

View the cat picture data associated with this git repository:

### Install Dat

```
npm install -g dat
```

### Download Data

1. Clone this repository
2. Open `index.html` in a browser (you should see missing pictures)
3. Download the data via dat
4. Refresh `index.html` and view cat pictures!

```
git clone https://github.com/joehand/dat-git-example.git
open ./dat-git-example/index.html
dat clone ./dat-git-example # download cat pictures & refresh!
```

#### Selective Sync

Including the `.datdownload` folder, you can specify only certain files to be downloaded by default. Download the selective files with:

```
git clone https://github.com/joehand/dat-git-example.git
dat clone ./dat-git-example --empty
dat sync ./dat-git-example
```
