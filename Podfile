platform :ios, '15.0'
target 'ViroSample' do
  use_frameworks!
  pod 'ViroReact', :path => '../node_modules/react-viro/ios/'
  pod 'ViroKit', :path => '../node_modules/react-viro/ios/dist/ViroRenderer/'
post_install do |installer|
  installer.pods_project.build_configurations.each do |config|
    config.build_settings["EXCLUDED_ARCHS[sdk=iphonesimulator*]"] = "arm64"
  end
end
