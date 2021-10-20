# Rhabit Coding Exercise

Welcome! As part of our interview process, we'll have you complete a small coding exercise. This is meant to test your aptitude without putting the stress of a live, in-person interview on you.

## The Exercise

This exercise is required to be completed with Ruby on Rails, which is what Rhabit is built on. It is composed of several specs, and your goal will be to complete as many as possible in the allotted time period (4 Hours). The exercise is meant to mirror **real** work that we do as developers at Rhabit, and as such, you are welcome to use online resources to help you complete it. However, please don't have another person help you with the challenge, it's designed to be a solo activity.

**Make sure you have a full 4 hours to commit to this exercise, once you've started, there is no pausing!**

## How it Works

This repo is a skeleton Rails application, where we've done the work setting up a new Rails 6 app. Familiarize yourself with the setup, take some time to make sure can start up a server and that everything is working as expected before continuing. If you're new to Rails, we recommend getting yourself acquainted with the framework before starting.

The bulk of the challenge will be reading the specs, determining what they're requiring, and writing code to fulfill them. We've intentionally left the skeleton mostly empty so that you have time to set up before the exercise starts.

When you're ready, you'll enter the name of this repo into `https://rhabit-hiring.herokuapp.com/`. This will copy over and commit the spec files into this repository. Once this has happened you'll have 4 hours to attempt the exercise. When you're done, make sure to commit and push your work so that we can review your work.

**Note: We will only consider code that is commited and pushed within the 4 hour timeframe, make sure to commit early and often!**

### Example Spec

Below is a sample of what one of the specs might look like:

```
RSpec.describe MyMath do
  describe "sum" do
    it 'returns the sum of two numbers' do
      expect(MyMath.sum(1, 3)).to eq(4)
    end
  end
end
```

You will have to write code that gets the spec to pass:

```
module MyMath do
  def self.sum(first_number, second_number)
    return first_number + second_number
  end
end
```

## Setup

### Clone this repository

`git clone https://github.com/Tshamp7/{repository-name}.git`

### Install gems

`bundle install`

### Setup the database

`rake db:setup`

## Running the Specs

After you've begun the challenge, you can run the specs with `rspec spec/`

## Troubleshooting

- If you're having trouble getting the specs to run, try prepending your commands with `bundle exec`

## Beginning the Exercise

Before you start:

- Run `rake db:setup RAILS_ENV=test` and make sure it completes without errors

Start the exercise:

1. Visit https://rhabit-hiring.herokuapp.com/
2. Enter the name of this github repository (rhabit-challenge-{code}) into the form
3. Click submit
4. At this point, your 4 hours has begun. The specs will be commited to this repository, so use `git pull` to grab them on your local version.

## Final Notes

### Make sure you are reading the spec files once they are added!  They are verbose and explicit about what they are looking for.  If you are going purely off of console output it will be much more difficult.

