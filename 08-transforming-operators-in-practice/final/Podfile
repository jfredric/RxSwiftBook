use_frameworks!
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '12.0'

target 'GitFeed' do
  pod 'RxSwift', '4.4.1'
  pod 'RxCocoa', '4.4.1'
  pod 'Kingfisher', '4.10.1'
end

post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['SWIFT_VERSION'] = '4.2'
        end
    end
end
