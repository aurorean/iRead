# Uncomment this line to define a global platform for your project
# platform :ios, '10.0'

target 'iRead' do
  # Comment this line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for iRead

  pod 'Localize-Swift', 	'~> 1.6'
  pod 'Alamofire',          '~> 4.0'
  pod 'AlamofireImage', 	'~> 3.0'
  pod 'ReachabilitySwift', 	'~> 3'
  pod 'RealmSwift'
  pod 'SwiftyUserDefaults'
  pod 'Ruler', 				'~> 1.0.0'
  pod 'Proposer'
  pod 'Kingfisher'
  pod 'NVActivityIndicatorView'
  pod 'SCLAlertView'
  pod 'DZNEmptyDataSet'
  pod 'RSBarcodes_Swift', 	:git => 'https://github.com/yeahdongcn/RSBarcodes_Swift.git', :branch => 'Swift-3.0'
  pod 'SnapKit',            '~> 3.0'
  pod 'SwiftyJSON', 		:git => 'https://github.com/appsailor/SwiftyJSON.git', :branch => 'swift3'
  pod 'TextFieldEffects', 	:git => 'https://github.com/raulriera/TextFieldEffects.git', :tag => '1.3.0'
  
  # Updated from martin_case1 branch.
  # Add more from martin_case2 branch.
  # Modified in Central Develop Branch.
  # Modified in Central Develop Branch 2nd time.
  
  # Verify PR revert process.
  
  pod 'Koloda',             :git => 'https://github.com/Yalantis/Koloda.git', :branch => 'swift-3'
  pod 'LTMorphingLabel', 	:git => 'https://github.com/lexrus/LTMorphingLabel.git', :branch => 'swift3'

  pod 'CBStoreHouseRefreshControl'
  pod 'ChameleonFramework/Swift', 	:git => 'https://github.com/ViccAlexander/Chameleon.git', :branch => 'swift3'
  pod 'MonkeyKing', 		'~> 1.0.0'


  target 'iReadTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'iReadUITests' do
    inherit! :search_paths
    # Pods for testing
  end

end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['SWIFT_VERSION'] = '3.0' # or '3.0'
    end
  end
end
