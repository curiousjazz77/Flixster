# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'JazzsFlixster' do
  # Comment the next line if you don't want to use dynamic frameworks
  #platform :ios, '10.0'
  use_frameworks!

  # Pods for JazzsFlixster
  pod 'Alamofire', '~> 4.4'
  pod 'AlamofireImage'
  # Add additional dependencies
  #pod 'OAuthSwift', '~> 1.1.0'
  #pod 'OAuthSwiftAlamofire'

  post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings.delete 'IPHONEOS_DEPLOYMENT_TARGET'
      end
    end
  end

  target 'JazzsFlixsterTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'JazzsFlixsterUITests' do
    # Pods for testing
  end

end
