    platform :ios, '9.0'

    use_frameworks!


        target ‘VuukleNestedCommentsExample’ do
        use_frameworks!

        pod ‘Vuukle’, :git => 'https://github.com/b13markus/Vuukle_comments_test', :branch => ‘swift_3’

    end

post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['SWIFT_VERSION'] = '3.0'
        end
    end
end