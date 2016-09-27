

platform :ios, '9.0'

use_frameworks!


target ‘VuukleNestedCommentsExample’ do
  # Comment this line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!


   pod ‘Vuukle’, :git => 'https://github.com/vuukle/vuukle_iOS_SDK.git', :branch => ‘swift_3’

end

post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['SWIFT_VERSION'] = '3.0'
        end
    end
end