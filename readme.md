# Dat Git Example

Example of adding your dataset to an existing Git repository and downloading via Dat!

* Add the `dat.json` file from your dat to git
* (optional) Add `.datdownload` to specify which files users will download by default.
* Add instructions, similar to below, on how to download data via dat.

## Usage

View the cat picture data associated with this git repository:

### Install Dat

```
npm install -g dat
```

### Download Data

1. Clone this repository
2. Download the data via dat
3. View cat pictures!

```
git clone https://github.com/joehand/dat-git-example.git
dat clone ./dat-git-example --empty
dat sync ./dat-git-example
```

