##### Block self
Prefix: `bself`
```objc
__block __typeof__(self) blockSelf = self;
```
##### Kiwi Should Eventually be No
Prefix: `ssbn`
```objc
[[expectFutureValue(theValue(<#something#>)) shouldEventually] beNo];
```
##### Kiwi Should Eventually be Yes
Prefix: `ssby`
```objc
[[expectFutureValue(theValue(<#something#>)) shouldEventually] beYes];
```
##### Kiwi Should be No
Prefix: `sbn`
```objc
[[theValue(<#something#>) should] beNo];
```
##### Kiwi Should be Yes
Prefix: `sby`
```objc
[[theValue(<#something#>) should] beYes];
```
##### Kiwi Spec
Prefix: `kiw`
```objc
#import "Kiwi.h"
#import "<#SomeFile#>.h"

SPEC_BEGIN(<#SomeFile#>Spec)

<##>

SPEC_END

```
##### Kiwi before each
Prefix: `bef`
```objc
beforeEach(^{
    <##>
});
```
##### Kiwi context
Prefix: `con`
```objc
context(@"<#something#>", ^{
    <##>
});
```
##### Kiwi describe
Prefix: `des`
```objc
describe(@"<#something#>", ^{
    <##>
});
```
##### Kiwi it
Prefix: `it`
```objc
it(@"<#something#>", ^{
    <##>
});
```
##### Kiwi should equal
Prefix: `seq`
```objc
[[<#something#> should] equal:<#something#>];
```
##### Kiwi should eventually equal
Prefix: `sseq`
```objc
[[expectFutureValue(<#futureValue#>) shouldEventually] equal:<#(id)#>];
```
##### Kiwi stub and return
Prefix: `snr`
```objc
[<#something#> stub:@selector(<#selector#>) andReturn:<#something#>];
```
##### Kiwi stub and return with arguments
Prefix: `snra`
```objc
[<#something#> stub:@selector(<#selector#>) andReturn:<#something#> withArguments:<#args#>,nil];
```
##### Kiwi theValue
Prefix: `tv`
```objc
theValue(<#expr#>)
```
##### Weak self
Prefix: `wself`
```objc
__weak __typeof__(self) weakSelf = self;
```
