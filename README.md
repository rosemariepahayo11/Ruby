# RubyGem
# ![Ruby](https://raw.githubusercontent.com/rosemariepahayo11/Ruby/main/%E2%9C%A8%24RubyGems%E2%9C%A8.png)

# RubyGems.org (née Gemcutter)
The Ruby community's gem host.

## Purpose

* Provide a better API for dealing with gems
* Create more transparent and accessible project pages
* Enable the community to improve and enhance the site

## Support

<a href="https://rubytogether.org/"><img src="https://rubytogether.org/images/rubies.svg" width=200></a>
<a href="https://rubycentral.org/"><img src="doc/ruby_central_logo.png" height=110></a><br/>

[RubyGems.org](https://rubygems.org) is managed by [Ruby Central](https://rubycentral.org), a community-funded organization supported by conference participation for [RailsConf](https://railsconf.org) and [RubyConf](https://rubyconf.org) through tickets and sponsorships.

Hosting fees are paid by Ruby Central and CDN fees are generously donated by [Fastly](https://fastly.com).

Additionally, [RubyTogether](https://rubytogether.org) sponsors individuals to work on development and operations work for RubyGems.org which augments volunteer efforts from the Ruby community.

[Learn more about our sponsors and how they work together.](https://rubygems.org/pages/sponsors)

# Links

* [Slack][]: #rubygems-org
* [RFCs](https://github.com/rubygems/rfcs)
* [Support](mailto:support@rubygems.org)
* [GitHub Workflow][]: [![test workflow](https://github.com/rubygems/rubygems.org/actions/workflows/test.yml/badge.svg)](https://github.com/rubygems/rubygems.org/actions/workflows/test.yml) [![lint workflow](https://github.com/rubygems/rubygems.org/actions/workflows/lint.yml/badge.svg)](https://github.com/rubygems/rubygems.org/actions/workflows/lint.yml) [![docker workflow](https://github.com/rubygems/rubygems.org/actions/workflows/docker.yml/badge.svg)](https://github.com/rubygems/rubygems.org/actions/workflows/docker.yml)
* [Code Climate][]: [![Maintainability](https://api.codeclimate.com/v1/badges/7110bb3f9b765042d604/maintainability)](https://codeclimate.com/github/rubygems/rubygems.org/maintainability)
* [Code Climate][]: [![Test Coverage](https://api.codeclimate.com/v1/badges/7110bb3f9b765042d604/test_coverage)](https://codeclimate.com/github/rubygems/rubygems.org/test_coverage)

[Slack]: https://bundler.slack.com/
[github workflow]: https://github.com/rubygems/rubygems.org/actions/
[code climate]: https://codeclimate.com/github/rubygems/rubygems.org

## Contributions

Please follow our [contribution guidelines][].

[contribution guidelines]: https://github.com/rubygems/rubygems.org/blob/master/CONTRIBUTING.md

To get setup, please check out the [Development Setup][].

[development setup]: https://github.com/rubygems/rubygems.org/blob/master/CONTRIBUTING.md#development-setup

Our deployment process is documented on the wiki as well, there's a multi-step
[Checklist][] to run through.

[checklist]: https://github.com/rubygems/rubygems-infrastructure/wiki/Deploys

Also please take note of our [Code of Conduct](https://github.com/rubygems/rubygems.org/blob/master/CODE_OF_CONDUCT.md).

If you have any trouble or questions getting set up please create an issue on this repository and we'll be happy to help!

# Organization

RubyGems.org consists of a few major parts:

* Rails app: To manage users and allow others to view gems, etc.
* Gem processor: Handles incoming gems and storing them in Amazon S3 (production) or
  on the filesystem in `server/` (development).
# RubyGems
Homepage:rubygems.org

# Announcements:
https://blog.rubygems.org

# Documentation:
https://guides.rubygems.org

# Support:
https://help.rubygems.org

# Source:
https://github.com/rubygems/rubygems

# Bugtracker:
https://github.com/rubygems/rubygems/issues

# DESCRIPTION
RubyGems is a package management framework for Ruby.

This gem is an update for the RubyGems software. You must have an installation of RubyGems before this update can be applied.

See Gem for information on RubyGems (or `ri Gem`)

To upgrade to the latest RubyGems, run:

$ gem update --system  # you might need to be an administrator or root
See UPGRADING.rdoc for more details and alternative instructions.

If you don't have RubyGems installed, you can still do it manually:

# Download 
from: rubygems.org/pages/download

Unpack into a directory and cd there

# Install 
with: ruby setup.rb # you may need admin/root privilege

For more details and other options, see:
ruby setup.rb --help

# GETTING HELP

Support Requests
Are you unsure of how to use RubyGems? Do you think you've found a bug and you're not sure? If that is the case, the best place for you is to file a support request at help.rubygems.org.

Filing Tickets
Got a bug and you're not sure? You're sure you have a bug, but don't know what to do next? In any case, let us know about it! The best place for letting the RubyGems team know about bugs or problems you're having is on the RubyGems issues page at GitHub.

Bundler Compatibility
See bundler.io/compatibility for known issues.



























https://rubycentral.org/

