# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'Kontalk' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Kontalk
  pod 'XMPPFramework/Swift'
  pod 'SwiftyBeaver'
  pod 'Fabric'
  pod 'Crashlytics'
  pod 'Alamofire', '~> 4.7'
  pod 'SwiftEventBus', :tag => '3.0.1', :git => 'https://github.com/cesarferreira/SwiftEventBus.git'
  
  # UI
  pod "FlagPhoneNumber"
  pod 'RAMAnimatedTabBarController'
  pod 'NVActivityIndicatorView'
  
  pod 'RxSwift',    '~> 4.0'
  pod 'RxCocoa',    '~> 4.0'

  target 'KontalkTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'KontalkUITests' do
    inherit! :search_paths
    # Pods for testing
  end

end
