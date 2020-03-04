use_frameworks!
source 'https://github.com/CocoaPods/Specs.git'
inhibit_all_warnings!

abstract_target 'TweetieAbstract' do
    pod 'Alamofire'

    pod 'RxSwift', '4.4.1'
    pod 'RxCocoa', '4.4.1'
    pod 'RealmSwift', '3.12.0'
    pod 'RxRealm', '0.7.6'
    pod 'Unbox', '3.0.0'
    pod 'Then', '2.2.1'
    pod 'Reachability', '3.2.0'
    pod 'RxRealmDataSources', '0.2.10'

    target 'Tweetie' do
        platform :ios, '12.0'
        pod 'RxDataSources', '3.1.0'
    end
    
    target 'MacTweetie' do
        platform :osx, '10.14'
    end
    
    target 'TweetieTests' do
        platform :ios, '12.0'
        pod 'RxTest', '4.4.1'
        pod 'RxBlocking', '4.4.1'
    end
end
