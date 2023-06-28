# Uncomment the next line to define a global platform for your project
 platform :ios, '13.0'

inhibit_all_warnings!

install! 'cocoapods',
:warn_for_unused_master_specs_repo => false
         :generate_multiple_pod_projects => true

def pods_rx
  pod 'NSObject+Rx'
  pod 'RxCocoa'
  pod 'RxSwift'
  pod 'RxDataSources'
  pod 'RxSwiftExt'
end

target 'SwiftStudy' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for SwiftStudy
  pods_rx
  
  pod 'KeychainAccess'
  pod 'Kingfisher'
  pod 'KingfisherWebP'
  pod 'Moya'
  
  pod 'SnapKit'
  pod 'SwiftLint'
  
  pod 'Then'
  pod 'UIAdapter'


end
