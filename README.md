# Github Actions

Learn about github actions


## Fast lane

1. Create Gemfile
2. Add ruby url and fastlane gem
3. Set local bundle path using bundle config set --local tepath 'vendor/cache'
3. Bundle install
4. Generate Fastlane files


## Match
1. Create private repo
2. Run bundle exec fastlane match init
3. Import .cer and .p12 files first using fastlane match import --readonly true --type appstore or development
4. Generate provisioning profiles using command bundle exec fastlane match appstore or development
