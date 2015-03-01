platform :ios, '7.0'

pod 'Cordova'             # Required
pod 'CordovaPlugin-file'  # Cordova plugin dependency
pod 'AFNetworking'        # Non-Cordova dependency

# Test target must not link against default pods (exclusive)
target 'HelloTests', :exclusive => true do
  pod 'OCMock'
end
