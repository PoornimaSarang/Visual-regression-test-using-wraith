# Visual-regression-test-using-wraith
The advent of rich and responsive UI design has made testing of webapps and websites next to impossible without focusing on CSS and visual layout. We as humans are not natural in spotting visual differences due to change blindness.

## Dependencies

1. ImageMagick  
	`brew install imagemagick`
2. Ruby  
	`rvm install <ruby-version>` replace &lt;ruby-version&gt; with version specified in [.ruby-version](.ruby-version)
3. Casperjs  		
	`brew install casperjs`
4. npm  		
	`brew install npm`
5. bundle  		
	`gem install bundle`

## Setup

$ `bundle install`  
$ `npm install`  

## Running the tests

$ `PATH=$(npm bin):$PATH`  
$ `bundle exec wraith capture configs/capture.yaml`  
