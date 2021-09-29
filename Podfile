# This Podfile mimics dependencies pinned using Cartage 
# to perform OSA scan with Checkmarx (which do not support Carthage)

platform :ios, '12.4'

swift_version = '5.0'

target 'OSA' do

  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  pod 'youtube-ios-player-helper', :git => 'https://github.com/youtube/youtube-ios-player-helper', :commit => '5882789964ab7876c6a91dc905669535c0a90f92'
  
  pod 'Bond', '~> 7.0.0' # transitive deps: Differ, ReactiveKit
  pod 'SnapKit', '~> 5.0'
  pod 'Swinject', '~> 2.7'
  pod 'SwinjectAutoregistration', '~> 2.7'
  pod 'FloatingPanel', '~> 2.0' # 2.3.1 is latest
  pod 'SwiftSoup', '2.2'
  pod 'SwiftProtobuf'
  pod 'AppCenter', '~> 4.3'
  pod 'Alamofire', '~> 4.9.1'
  pod 'ZIPFoundation', '~> 0.9.12'

end
