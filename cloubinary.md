### Cloudinary

- https://cloudinary.com/users/login

- Gemfile: gem 'cloudinary'

- uploaders -> image_uploader.rb -> include Cloudinary::CarrierWave

- You can download your customized cloudinary.yml configuration file through our Management Console. https://cloudinary.com/documentation/rails_integration

- config -> cloudinary.yml

- config -> storage.yml =
  ` cloudinary:
  service: Cloudinary`

- config -> environments -> development.rb = config.active_storage.service = :cloudinary