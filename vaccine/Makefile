vaccine:
	xcrun clang -x objective-c -arch x86_64 -framework Foundation -mmacosx-version-min=10.11 -g -fobjc-arc -Wall -Werror vaccine.m  -Wl,-sectcreate,__TEXT,__info_plist,Info.plist -o ../build/$(PRODUCT_NAME)

