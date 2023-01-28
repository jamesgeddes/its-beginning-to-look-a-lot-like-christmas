<!--- STANDARD README -->
<!--- https://github.com/RichardLitt/standard-readme -->
<!--- ---------------------------------------------- -->
<!--- Title -->
<!--- must match repository name -->
<!--- REQUIRED -->

# itsbeginningtolookalotlikechristmas

<!--- Banner -->
<!--- OPTIONAL -->
<!--- Must not have its own title -->
<!--- Must link to local image in current repository -->


<!--- Badges -->
<!--- OPTIONAL -->
<!--- Must not have its own title -->


<!--- Short description -->
<!--- REQUIRED -->
<!--- An overview of the intentions of this repo -->
<!--- Must not have its own title -->
<!--- Must be less than 120 characters -->
<!--- Must match GitHub's description -->
Graphing Christmasyness over time

<!--- Long Description -->
<!--- OPTIONAL -->
<!--- Must not have its own title -->
<!--- A detailed description of the repo -->
IBTLALLC graphs the onset of Christmas through the popularity of the Perry Como
classic, "[It's Beginning to Look a Lot Like Christmas](https://youtu.be/KmddeUJJEuU)" over time.
Where [IsItChristmas.com](https://isitchristmas.com) gives you a simple yes or no, each year at
[ItsBeginningToLookALotLike.Christmas](http://ItsBeginningToLookALotLike.Christmas), tells you when
It's Beginning to Look a Lot Like Christmas.

## Table of Contents

<!--- REQUIRED -->

1. Background
2. Install
3. Usage
4. Contributing
5. License

<!--- ## Security -->
<!--- OPTIONAL -->
<!--- May go here if it is important to highlight security concerns. -->
<!--- Otherwise, it should be in Extra Sections. -->

## Background

<!--- OPTIONAL -->
<!--- Explain the motivation and abstract dependencies for this repo -->

### Why?

Computer Scientists like specific definitions of things, as that makes it easier to codify them.
Christmasyness is seemingly a very emotional state that would be almost impossible to design,
but in 1951, Perry Como and The Fontane Sisters with Mitchell Ayres & His Orchestra gave us the
perfect marker. The question, "Is it beginning to look a lot like Christmas?" can therefore be
answered with the specific definition of the popularity of the song "It's Beginning to Look a
Lot Like Christmas".

### How it works

[ItsBeginningToLookALotLike.Christmas](http://ItsBeginningToLookALotLike.Christmas) works by
polling the Spotify API every day to get the popularity of track ID
`2pXpURmn6zC5ZYDMms6fwa`. We then timestamp
this and chuck it at a pretty graph. Grab some Eggnog and watch Christmas cheer gradually spread
throughout the land.

### Future improvements

- Local radio<br />
  In the future, other sources will be added to further improve accuracy. Local radio stations
  will be sampled at regular intervals for the
  [fingerprint](https://en.wikipedia.org/wiki/Acoustic_fingerprint)
  of our favourite definition of Christmastime.
- Christmas map<br />
  When we include the location of those stations, we will also be able to _map_ the spread of
  Christmasyness over time. This will also allow us to produce a Christmas heatmap of the most
  Christmasy locales.

### Motivation

The motivation for this project is that it is,

- [rather silly](https://youtu.be/3ANufwUPFm8).
- able to show that the data driven mindset can be applied to all areas if you can just find the
  right metrics.
- a great demonstration of the principles of
    - DevOps
    - Continuous Integration
    - Continuous Delivery - [read the CD Bible now](https://amzn.to/3Wxh2GE)

It should be noted that this project is intended as a MVP.

## Install

<!--- Explain how to install the thing. -->
<!--- OPTIONAL IF documentation repo -->
<!--- ELSE REQUIRED -->

## Usage

<!--- REQUIRED -->
<!--- Explain what the thing does. Use screenshots or videos. -->

Simply head to [ItsBeginningToLookALotLike.Christmas](http://ItsBeginningToLookALotLike.Christmas).

### Self Host

If you want to build this in your own environment, perhaps on your favourite song,

1. Create accounts, fork & customise<br />
   Create accounts with AWS, Terraform, CircleCI and Harness. Change all variables to your own
   values.
2. Run Terraform<br />
   This gets the infrastructure in place.
3. Run CI - CircleCI<br />
   This builds the containers.
4. Run CD - Harness<br />
   This deploys the contains to AWS Lambda and the frontend HTML to S3.
5. Marvel in awe and wonder at your silly new thing<br />
   Your song tracker is now available at the domain you specified!

After manually running each pipeline the first time, subsequent runs will be triggered on commit
to main.

<!-- Extra sections -->
<!--- OPTIONAL -->
<!--- This should not be called "Extra Sections". -->
<!--- This is a space for 0 or more sections to be included, -->
<!--- each of which must have their own titles. -->


<!-- ## API -->
<!--- OPTIONAL -->
<!--- Describe exported functions and objects -->


<!-- ## Maintainers -->
<!--- OPTIONAL -->
<!--- List maintainer(s) for this repository -->
<!--- along with one way of contacting them (e.g. GitHub link or email). -->


<!-- ## Thanks -->
<!--- OPTIONAL -->
<!--- State anyone or anything that significantly -->
<!--- helped with the development of this project -->

## Contributing

<!--- REQUIRED -->
If you need any help, please log an issue.

PRs are welcome. My only request is that everyone should "Be excellent to each other".

## License

<!--- REQUIRED -->

- This is licensed under the GNU General Public License v3.0.
- The license owner is [James Geddes](https://jamesgeddes.pro/).
- The full text of the license can be found in the [LICENSE](LICENSE) file.