# Images App with CarrierWave

A basic images app demonstrating uploading images with the gem, CarrierWave.

## Dependencies
- CarrierWave Gem: 

## Install
- Clone from Github
- Add carrierwave gem to gemfile
```ruby
  # Upload Images
  gem 'carrierwave', '~> 1.2', '>= 1.2.1', github: 'carrierwaveuploader/carrierwave'
```

Then...

```ruby
 bundle update  
 bundle install 
 rails db:migrate

 # Run tests
 rails test

 # If pass tests, run server
 rails server
```

- Go to: localhost:3000
- Upload images

  
## Notes

- When using CarrierWave, after creating the uploader...
 ```rails g uploader image```
  Make sure to stop and restart the rails server or will get an "uninitialized" error



## References
- [Source: Github: CarrierWave](https://github.com/carrierwaveuploader/carrierwave)
- [RubyGems: CarrierWave](https://rubygems.org/gems/carrierwave)

- [Rails5 & CW](https://code.tutsplus.com/tutorials/rails-image-upload-using-carrierwave-in-a-rails-app--cms-25183)
- [Rails5 & CarrierWave](https://medium.com/@mauddev/rails-5-and-carrierwave-53960ec20c4b)
- [Rails4 & CarrierWave](https://www.tutorialspoint.com/ruby-on-rails/rails-file-uploading.htm)
- [GoRails: File Uploading in Rails with Carrierwave, CW info starts ~14:00](https://www.youtube.com/watch?v=Q8wF9RrJhrY)
- [Treehouse: Paperclip, CarrierWave & Dragonfly with Rails4](https://teamtreehouse.com/library/image-uploads-in-ruby-on-rails-41)
- [RailsCast: Rails4, #253 CarrierWave File Uploads](http://railscasts.com/episodes/253-carrierwave-file-uploads?autoplay=true)








