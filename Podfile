source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '10.0'

target 'AppChain' do
  use_frameworks!
  use_modular_headers!
  inhibit_all_warnings!

  pod 'web3swift', git: 'https://github.com/matterinc/web3swift', tag: '1.1.10'
  pod 'SwiftProtobuf', git: 'https://github.com/apple/swift-protobuf.git', tag: '1.0.3'

  target 'AppChainTests' do
    inherit! :search_paths
  end
end
