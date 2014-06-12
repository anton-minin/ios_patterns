����������� iOS ���������. �� ������
=====================================
---
V1.1

���� ������

### 
����������

[������](#intro)
[������� ���������](#changelog)
[Prototype](#prototype)
[Factory Method](#factorymethod)
[Abstract Factory](#abstractfactory)
[Builder](#builder)
[Singleton](#singleton)
[Adapter](#adapter)
[Bridge](#bridge)
[Facade](#facade)
[Mediator](#mediator)
[Observer](#observer)
[Composite](#composite)
[Iterator](#iterator)
[Visitor](#visitor)
[Decorator](#decorator)
[Chain of responsibility](#cor)
[Template Method](#templatemethod)
[Strategy](#strategy)
[Command](#command)
[Flyweight](#flyweight)
[Proxy](#proxy)
[Memento](#memento)


### <a name="intro"></a>������
������, ����! ����� ����, ��� �� ����� ��������� ��� �����. ��, ��� ������ ������, ����� ����������, ��� ��� ���������. � ��������� ����� ������ ������� ���������� ��������� GoF ��� iOS. ��� ��� ������� ������ �� Objective-C, ��������� ����� �� ����� ������������ � ��� Mac, �� ��� ��� � ����� ���������, ��� �Hello, World!� ��� Mac �� ����� � �� ���������� �� ����.

��� ���� ���� ������? ����������, �� ��������! � ��������� ����� �������������� ������, ������ ��� � ������ ��������� �� ���� ������ ��� ������. �� � ������������ �������, ��� �������� ������ ������, ������� �� ��� �������� �� <diwingless@gmail.com>. � ����� �������, ��� �� �� ������� ����, � �������� ��� ��������� ������, �, ������� ��, ������� �� ������, �������� � ��������� ���������� � �����.

### ��� ���� ��� �����?

����� ����� ������� ���� iOS �������������, ������ ��� ����� ������ ������� ������. �������, ��� �������� ������. ��� ���������� �������������, ����� ����� ��������� ��� �������� � ������� �� ����������, � ������� ��� ��� ��� ������� �� �������������. ��� ����� ����������� �����, ����� ����� ��������� ��������� ������������ ��� ������� �������� ���������. ����� ���������� �� ������ ����� ������� �� Obj-�, � �������� �� �� ���� �� ������� �������� ������ Angry Birds, ������ ��������� �������� ��� ��� ��� �� ������ �������. �������� ������ ������ �����, ����� ��������������� ���� ������ � ������ :)

### ������ ��� �����?

�� ����� ������� ������� ��������� � ������ ������ ���� ���������. ������ �����������, ��� ������ ���� �� ������������, ���� �� � ��� �������� ���� ���������� �� �� ����������� ������������� �����, � �� ����������� ������������ � �������. � ���������, � �� ���������, ������� �������� ��������� �� ����, � �� ������, ������� �������� ������������ :) ������, � ��������� ���������� ��������, ������� ���� � ����. ��� ���� ������ � � ������ �� ������, � ���� ������� � ��������� ���� ����� ������ ��� � ������ ��-�� ������ ������ ����� � ��� �������, ������� � ��� ����� ���������� ��������. ������������ �������� ������, ��� ����� ���� �� ���� ����� ������, ����� ��� ���� �������� ������ (�� � ���� �������, ����� ������). 

### ��������������� �����

����� ��������� :) ����� ������ ������, �������� ���� �� ��������� ���������� �����. ���������������� ����� ����� ����� ���������� ������ ������. � �� ����� ����, ����� �������� � ����, �� � � ������ ������ ��� ���������� ��� �����. ������, ������ ���� ������:

1.	����� �� ������ �����������. ����� ����� ������ ��������� ���������������� � ����� ����, �� �� ������ ���. ������.
2.	����� ����� ��������������, ���������� ���� � ����, �������� ��������� ������ � ���� ������ ��� ������. ���� ��������� ������ ��������� ����� � ������� ��� � �������, ���� ��� � ��� ���� �������, ��������, � ��� ���� �������.
3.	�����������, ����� �� ����� ��������������� �� �� ������, ������� �� ��� �������� :) �� �������� - ������� �����, �� � �� ��������. 
4.	�� ������ ���������� �����, �������� � ����� �����, �� ����� ������ �����, ������� ������.
5.	���� �� �������� ������� �����, ���� ���� ������� � ��� ��� ���� ����� :) �������������! �� ����� �������!
6.	������ ��, ������ ����� ���, ����� ���� ������� ������. 
7.	����� ��������� ����� �����������, ������ �������� ������ ���������� ��. ��������� �����, �� ������ ���������� ���������� � ���������� ����, ������� �������� ���-�� � ���� ����! �����������! ��� ���� ���������!

### ������������� �����

�������. 

### <a name="changelog"></a>������� ���������
����� �� �� ��������, ������ ����� ����������� �������� � ����������������! 

- V1.0 � ������� ������� �����
- V1.1 � ���������� ���, ������� ��������� ������, ����� �������� � ���� ����

## <a name="prototype"></a>Prototype
�������� � ���� �� ����� ������� ���������, ������� ��������� ��� �������� ������ ����� ������������ �������. �� ���� ������������ ��� �������� ��� ������ �������

#### ����� ������������:

1.	� ��� ���� ��������� ������ ��������, ������� ����� �������� ������ � ��������� �� �����.
2.	����� ������� ������ ��� ���� ������ ����� �����, ���� � ������ �����. �������� ���� ���� ������ ������� �� ��� ����� ���� ��������, ������ �� ������� ��� ���������� ������� ��������� ����� �� ����, ���-�������� � ���� �������� ����������. ����� ����� ����������� ������ � �������� ��������� �����
3.	�� � � ��������, ��� ����� � �� �����, ��� ��������� ������. �� ���� � ����. 
4.	��� ������� ���� ������ �������� ������ (����� ������), ������� ����� ��������������� ��� ��������� ������ �������� �������.

��, � ���� ��� ������ ����������� (��������� ����� �� ��������) � �������� � ��� �������, ������� ������� �� ������ ��������������, � ������ ������ ��� �������� ���� �������� ��������. ����, ������, ��� ������� � ���� ���������� ���������� ����. ����������, ��� ������ �� ������ ������ ���������� ����� ������, ������� � ��� � ����������.

#### ������������� � �������� �����������
��� �������� ������� � .NET ����. ���� ���������, ���� �������� � ����.

������������� ����������� � ��� ������ �������� ������ ��������� �� �� �� ����� ����� � ����. �� ����, � ���������� �� ����� �������� ��� �������, ������� ��������� �� ���� � �� �� ��������.

� �������, �������� ������:
``` objective-c
@interface Person : NSObject <NSCopying>

@property (nonatomic,weak) NSString *name;
@property (nonatomic,weak) NSString *surname;
@property (nonatomic,weak) NSString *age;

@end
```
� ������ ������� ������ �������� ��� ������� � ���������, ��� �� ���������:

``` objective-c
Person *firstPerson = [[Person alloc] init];
firstPerson.name = @"Dima";
firstPerson.surname = @"Surname";
Person *secondPerson = firstPerson;
NSLog(@"First Person name  = %@ and surname = %@", 
        firstPerson.name, firstPerson.surname);
secondPerson.name = @"Roma";
NSLog(@"Second Person name  = %@ and surname = %@", 
        secondPerson.name, secondPerson.surname);
NSLog(@"First Person name  = %@ and surname = %@", 
        firstPerson.name, firstPerson.surname);
```

��� ����� ��� ���������� ���������:

>2013-01-21 01:31:20.986 PrototypePattern[1961:11303] First Person name  = Dima
>
>2013-01-21 01:31:20.987 PrototypePattern[1961:11303] Second Person name  = Roma
>
>2013-01-21 01:31:20.987 PrototypePattern[1961:11303] First Person name  = Roma

��������, ��� ���� � ������ �� ��� ��� `secondPerson`, �� � � `firstPerson` ��� ����������. ������ ������ ��� �� ������� ��� ��������� �� ���� � ��� �� ������.

��� ����� �����, ����� ������������ �������� �����������, ������� � Objective-C ������� � �������� ����� ������ ��� � � .NET:

��� ����� ���� ����������� �������� NSCopying, � �����������:

``` objective-c
-(id) copyWithZone:(NSZone *)zone;
```

� ��, �� ����� ����������, ��� �� �� ��������� ����� `copy`. �� ��� ���� � ������ `NSObject`. ���� ������� ���� ����� � �� ����������� `copyWithZone`, �� �� ������� ������ ���� `NSInvalidArgumentException`.

������ ��������� ������ ������� ������ ����� ��������� ��������� �������:

``` objective-c
@interface Person : NSObject <NSCopying>

@property (nonatomic,weak) NSString *name;
@property (nonatomic,weak) NSString *surname;
@property (nonatomic,weak) NSString *age;

-(id) copyWithZone:(NSZone *)zone;

@end
```

� ���� ����������:

``` objective-c
@implementation Person

-(id) copyWithZone:(NSZone *)zone
{
    Person *copy = [[self class] allocWithZone:zone];
    copy.name = self.name;
    copy.age = self.age;
    copy.surname = self.surname;
    return copy;
}

@end
```

������ ������� ������� ��� ������ ��������� ����������:

``` objective-c
Person *firstPerson = [[Person alloc] init];
firstPerson.name = @"Dima";
firstPerson.surname = @"Surname";
Person *secondPerson = firstPerson;
NSLog(@"First Person name  = %@ and surname = %@", 
		firstPerson.name, firstPerson.surname);
secondPerson.name = @"Roma";
NSLog(@"Second Person name  = %@ and surname = %@", 
		secondPerson.name, secondPerson.surname);
NSLog(@"First Person name  = %@ and surname = %@", 
firstPerson.name, firstPerson.surname);
```

�� �, �����������, ���:

>2013-01-21 01:48:36.538 PrototypePattern[2090:11303] First Person name  = Dima and surname = Surname
>
>2013-01-21 01:48:36.539 PrototypePattern[2090:11303] Second Person name  = Roma and surname = Surname
>
>2013-01-21 01:48:36.540 PrototypePattern[2090:11303] First Person name  = Dima and surname = Surname

��� �����, �� � ���������� �������� ��� ����������� �������, ���� �� ������� ������ �� ������� �������.

[��� �������.][PrototypePattern]

## <a name="factorymethod"></a>Factory Method.

��� ���� ����������� �������, �������� ����� � ���������. ������� ��������� ���������� �������� ������������� ��������, �� ����������� ������������� ������, ������ ����� �������������� ��������� �� ����� ������� ������, �� ������������� ������ ������ ������ ����� ������. ��������� ���� ������� �������� ����������� �����������, ��� �� ����� ������ ����� �������� ��� ��������������.

#### ����� ������������:

1.	�� �� �� ����� ������� ������ ������ ���� ��� ���������.
2.	�� ����� ����� �� ������������ ������ ����� ����� ��� ���������, � ��� ����������.

#### ������ ������ ������������:

�������, ��������� ��������� ������� � �����, ������ ��� � ��� ���� � ��� �� ������������ ������. ������, ���� �������������� �������� ����� ��������, �� ����� ��������� ����� ����, �� ����� ��� ���� ���, ������� ���������� ��������� �����.

#### ������:

������� ����������, ��� �� ����� ������������ �������, � ������� ��� ������ ����������� �� ���� :) �� ������ ������ ����� ���� 2� �����: ������� � ������.

� ���� �� �������� ������ ����, � ��� ���� ��������� �������, ������� �������.

��� ������ �������� ���� `Product`. ��� ���������� ��� ����� �� ����������, ���� �� ����� ��������� � ���� ����� ��� ������ ����� ������� ������ (������� ��� �������, �� �� ����� �� ����������):

``` objective-c
@interface Product : NSObject
@property(nonatomic) int *price;
@property(nonatomic, strong) NSString *name;
-(NSInteger *)getTotalPrice:(int)sum;
-(void)saveObject;
@end 

@implementation Product
-(NSInteger *) getTotalPrice:(int)sum
{
    return self.price + sum;
}

-(void) saveObject
{
    NSLog(@"I am saving an object in to product database");
}
@end
```

������ �������� ��� ���������� ����� ����������.

�������:

``` objective-c
@interface Toy : Product
@end 

@implementation Toy
-(void) saveObject
{
    NSLog(@"Saving object into Toys database");
}
@end
```

� ������:

``` objective-c
@interface Dress : Product
@end 

@implementation Dress
-(void) saveObject
{
    NSLog(@"Saving object into Dress database");
}
@end
```

�� ������ �� ����������� ������� �������� � ������ ��������. ����������, ������ ���� ������� �����, ������� ����� �� ���� ����������, ��� �� �� ������� � ��� � ����, � ��������� ������ ������������ ����.

``` objective-c
@interface ProductGenerator : NSObject

-(Product *) getProduct:(int)price;
@end 

@implementation ProductGenerator

-(Product *) getProduct:(int)price
{
    
    if ( price > 0 && price < 100 )
    {
        Toy *p = [[Toy alloc] init];
        return p;
    }
    
    if (price >= 100)
    {
        Dress *p = [[Dress alloc] init];
        return p;
    }
    return nil;
}
@end
```

�� ���, ����������, � ���. ������ ������ �������� �����, ������� ����� ������� � ���������� �������:

``` objective-c
-(void) saveExpenses:(int)aPrice
{
    ProductGenerator *pd = [[ProductGenerator alloc] init];
    
    Product *expense  = [pd getProduct:aPrice];
    
    [expense saveObject];
}
```

���������!	
``` objective-c
[self saveExpenses:50];
[self saveExpenses:56];
[self saveExpenses:79];
[self saveExpenses:100];
[self saveExpenses:123];
[self saveExpenses:51];
```

���:

>2013-01-23 23:27:54.223 FactoryMethodPattern[8833:11303] Saving object into Toys database
>
>2013-01-23 23:27:54.226 FactoryMethodPattern[8833:11303] Saving object into Toys database
>
>2013-01-23 23:27:54.226 FactoryMethodPattern[8833:11303] Saving object into Toys database
>
>2013-01-23 23:27:54.227 FactoryMethodPattern[8833:11303] Saving object into Dress database
>
>2013-01-23 23:27:54.227 FactoryMethodPattern[8833:11303] Saving object into Dress database
>
>2013-01-23 23:27:54.228 FactoryMethodPattern[8833:11303] Saving object into Toys database

[��� �������.][FactoryMethodPattern]
 
## <a name="abstractfactory"></a>Abstract Factory

����������� ������� � ��� ���� ����� ���������� �������, ������� ��� � ��������, ��� � � ���������� ������ ����� �� ��������� �����. 

����, ��� �� ������ ����������� �������:

����������� ������� ���� ������� ��������� ��� �������� ��������, ������� ����������� � ���� ��� ����� ���������� ��������.

#### ������� �� ���������� ������:

1.	��������� ����� ��������� ������� ������ � ���� �� ����, ������� �� ����� ��������� ����������� �������
2.	����� �������� ����� ��� ������� � ���� �������� ��������� �������, � ��������� ������ �� ����� ������ �������� ������������ ������, ������������� �� ���������� ��������.

������� ���������� ��������: � ��� ���� ��� ������� �� ������������ IPhone � IPad. ���� ������������, �������� Apple, ������ � ������ ������� ���. � ���, �� ����� ����������� ��� ������: ���� � ������ 3-�� ���� � �� ����� �� �������, � ������ ������ � ����� ������� ������������ ��������� Apple.

����, ����� � ��� ���� �������, ������� ����� ����������� � ������ � ������:

``` objective-c
@interface IPhoneFactory : NSObject

-(GenericIPhone *) getIPhone;
-(GenericIPad *) getIPad;

@end
```

�����������, ��� ���������� ����������� ��������, ������� ������� ����� �����������:

``` objective-c
@interface GenericIPad : NSObject

@property(nonatomic, weak) NSString *osName;
@property(nonatomic, weak) NSString *productName;
@property(nonatomic, strong) NSNumber *screenSize;

@end
 
//-----
 
@interface GenericIPhone : NSObject

@property (nonatomic, weak) NSString *osName;
@property (nonatomic, weak) NSString *productName;

@end
```

�� �������� ������� ����������.

����� � ��� ���� ��� ���� ��������� - ������������ Apple � ��������, ������� ����������� ������������ �������� ���:

``` objective-c
@interface AppleIPhone : GenericIPhone
@end 

@implementation AppleIPhone

-(id) init
{
    self = [super init];
    
    self.productName = @"IPhone";
    self.osName = @"iOS";
    
    return self;
}
@end
 
//--------
//�����
@interface AppleIPad : GenericIPad
@end 

@implementation AppleIPad
-(id) init
{
    self = [super init];
    self.productName = @"IPad";
    self.osName = @"iOS";
    self.screenSize = [[NSNumber alloc] initWithFloat:7.7f];
    
    return self;
}
@end
```

�����������:

``` objective-c
@interface ChinaPad : GenericIPad
@end
 
@implementation ChinaPad

-(id) init
{
    self = [super init];
    self.osName = @"Windows CE";
    self.productName = @"Buan Que Ipado Killa";
    self.screenSize = [[NSNumber alloc] initWithFloat:12.5f];
    
    return self;
}
@end
//--------
 
@interface ChinaPhone : GenericIPhone
@end
 
@implementation ChinaPhone

-(id) init
{
    self = [super init];
    
    self.osName = @"Android";
    self.productName = @"Chi Huan Hua Phone";
    
    return self;
}
@end
```

������ ��������, ������� ��, ������������ �� ��������� ��������, ������ �� ������ ������� �� �������! �������������� ��� ������ ��������� ������� Apple:

``` objective-c
@interface AppleFactory : IPhoneFactory
@end
 
@implementation AppleFactory

-(GenericIPhone *) getIPhone
{
    AppleIPhone *iphone = [[AppleIPhone alloc] init];
    return iphone;
}

-(GenericIPad *) getIPad
{
    AppleIPad *ipad = [[AppleIPad alloc] init];
    return ipad;
}
@end
```

������� �� � ������ ���������� ������� ���� ���� ���� �������:

``` objective-c
@interface ChinaFactory : IPhoneFactory
@end
 
@implementation ChinaFactory

-(GenericIPad *) getIPad
{
    ChinaPad *pad = [[ChinaPad alloc] init];
    return pad;
}


-(GenericIPhone *) getIPhone
{
    ChinaPhone *phone  = [[ChinaPhone alloc] init];
    return phone;
}
@end
```

��� �����, ������� ����������, � ��� ������� � ��� ��������� ������ :)

�� ���, ����������, � ���, �� ����������� ���, ��� ���� ��� ������������! ������ ������� ������� ��������� ����� ������� ����� ���������� ��� �������, ������� �� ����� (������, ��� ��������� ����� ���� �����):

``` objective-c
-(IPhoneFactory *) getFactory
{
    if (_isThirdWorld)
        return [[ChinaFactory alloc] init];
    
    return [[AppleFactory alloc] init];
}
```

������, �������-�� �������� ��������� ���������:

``` objective-c
_isThirdWorld = false;
IPhoneFactory *factory = self.getFactory;
GenericIPad *ipad = factory.getIPad;
GenericIPhone *iphone = factory.getIPhone;
NSLog(@"IPad named = %@, osname = %@, screensize = %@", 
			ipad.productName, ipad.osName, ipad.screenSize.stringValue);
NSLog(@"IPhone named = %@, osname = %@", iphone.productName, iphone.osName);
```

��� ����� ��������� ��������� �������:

>2013-01-26 20:00:56.663 AbstractFactory[13093:11303] IPad named = Buan Que Ipado Killa, osname = Windows CE, screensize = 12.5
>
>2013-01-26 20:00:56.665 AbstractFactory [13093:11303] IPhone named = Chi Huan Hua Phone, osname = Android

������, ������ ������� �������� ���������� '_isThirdWorld' �� 'false', � ��� ����� ������ ������:

>2013-01-26 20:02:21.745 AbstractFactory [13115:11303] IPad named = IPad, osname = iOS, screensize = 7.7
>
>2013-01-26 20:02:21.747 AbstractFactory [13115:11303] IPhone named = IPhone, osname = iOS

[��� �������.][AbstractFabric]

## <a name="builder"></a>Builder

��� �����������, ��� � ��� ���� �������. �� � ������� �� ������� �� ����������� �����, ��� ����� ��������� ������ �������� �� ���� ��������, � ��� ��� ���� ��������� ������������. ������, ���� ���� ������, �� ��� ���� ��� ��������� ����� ���� ���������� ������, � ��� �����������, ���� ��� ����� ������ ���������, � �� ����� �������� ����� ������� ��� � ��������� ������� �������� ��������. ������ � ����� ������� ��� ����� �������� ����� ������� ��� ���������.

#### ����� ������������:

1.	�������� �������� �������
2.	������� �������� ������� ���� ����� ������������� � � �������, ��������� ������ �� ���� � ����������� ���.

��� ������� ������� �� ���� ��������� � Bulilder � Director. Builder ���������� ������ ����������� �������, � Director ����� ����� Builder ������������, ����� ������ ����������� �������. ���������!

����� � ��� ���� �������, ������� �������� ���������� ����������:

``` objective-c
@interface AndroidPhone : NSObject

@property (nonatomic, weak) NSString *osVersion;
@property (nonatomic, weak) NSString *name;
@property (nonatomic, weak) NSString *cpuCodeName;
@property (nonatomic, strong) NSNumber *RAMsize;
@property (nonatomic, strong) NSNumber *osVersionCode;
@property (nonatomic, weak) NSString *launcher;
@end
```

������� �������� �������� ���������, �� �������� ����� ������������� ���������� ���������:

``` objective-c
@interface BPAndroidPhoneBuilder : NSObject

@property (nonatomic, strong) AndroidPhone* _phone;

-(void) setOSVersion;
-(void) setName;
-(void) setCPUCodeName;
-(void) setRAMSize;
-(void) setOSVersionCode;
-(void) setLauncher;

-(AndroidPhone *) getPhone;

@end

//---

@implementation BPAndroidPhoneBuilder

-(id) init
{
    self = [super init];
    
    self._phone = [[AndroidPhone alloc] init];
    
    return self;
}

-(AndroidPhone *) getPhone
{
    return self._phone;
}

@end
```

�� � ������ ������� ��� ��� ���������� ����������. � �������, ��� �� �������� ��������� ��� �������� ��������:

``` objective-c
@interface LowPricePhoneBuilder : BPAndroidPhoneBuilder
@end

//----
@implementation LowPricePhoneBuilder

-(void) setOSVersion
{
    self._phone.osVersion = @"Android 2.3";
}
-(void) setName
{
    self._phone.name = @"Low price phone!";
}
-(void) setCPUCodeName
{
    self._phone.cpuCodeName = @"Some shitty CPU";
}
-(void) setRAMSize
{
    self._phone.RAMsize = [[NSNumber alloc] initWithInt:256];
}
-(void) setOSVersionCode
{
    self._phone.osVersionCode = [[NSNumber alloc] initWithFloat:3.0f];
}
-(void) setLauncher
{
    self._phone.launcher = @"Hia Tsung!";
}
@end
```

�, ������� ��, ������������� �������� ��������:

``` objective-c
@interface HighPricePhoneBuilder : BPAndroidPhoneBuilder
@end

//----

@implementation HighPricePhoneBuilder

-(void) setOSVersion
{
    self._phone.osVersion = @"Android 4.1";
}
-(void) setName
{
    self._phone.name = @"High price phone!";
}
-(void) setCPUCodeName
{
    self._phone.cpuCodeName = @"Some shitty but expensive CPU";
}
-(void) setRAMSize
{
    self._phone.RAMsize = [[NSNumber alloc] initWithInt:1024];
}
-(void) setOSVersionCode
{
    self._phone.osVersionCode = [[NSNumber alloc] initWithFloat:4.1f];
}
-(void) setLauncher
{
    self._phone.launcher = @"Samsung Launcher";
}
@end
```

���-�� �� ������ ������������ ����������, ������ ������� �������� ������, ������� ����� � ������� ���������� ��������� ������� ��� ������� ��������:

``` objective-c
@interface FactorySalesMan : NSObject

@property (nonatomic, strong) BPAndroidPhoneBuilder *_builder;

-(void) setBulider:(BPAndroidPhoneBuilder *)aBuilder;
-(AndroidPhone *) getPhone;
-(void) constructPhone;

@end

//----

@implementation FactorySalesMan

-(void)setBulider:(BPAndroidPhoneBuilder *)aBuilder
{
    self._builder = aBuilder;
}

-(AndroidPhone *) getPhone
{
    return self._builder.getPhone;
}

-(void) constructPhone
{
    [self._builder setOSVersion];
    [self._builder setName];
    [self._builder setCPUCodeName];
    [self._builder setRAMSize];
    [self._builder setOSVersionCode];
    [self._builder setLauncher];
}

@end
```

�� � ������� �� ���� �� ��� ����� � ����:

``` objective-c
LowPricePhoneBuilder *_cheapPhoneBuilder = [[LowPricePhoneBuilder alloc] init];
HighPricePhoneBuilder *_expensivePhoneBuilder = 
					[[HighPricePhoneBuilder alloc] init];

FactorySalesMan *_salesMan = [[FactorySalesMan alloc] init];
[_salesMan setBulider:_cheapPhoneBuilder];
[_salesMan constructPhone];
AndroidPhone *_phone = [_salesMan getPhone];
    
NSLog(@"Phone Name = %@, osVersion = %@, cpu code name = %@, ram size = %@, os version code = %@, launcher = %@", 
_phone.name, _phone.osVersion, _phone.cpuCodeName, _phone.RAMsize, _phone.osVersionCode, _phone.launcher);
    
[_salesMan setBulider:_expensivePhoneBuilder];
[_salesMan constructPhone];
_phone = [_salesMan getPhone];
NSLog(@"Phone Name = %@, osVersion = %@, cpu code name = %@, ram size = %@, os version code = %@, launcher = %@",
_phone.name, _phone.osVersion, _phone.cpuCodeName, _phone.RAMsize, _phone.osVersionCode, _phone.launcher);
```

��� �����, �� ������� ��������� ����������, �, ������ ��������� ('FactorySalesMan') ����� ��������� �� ����� ������������, �� �������� ��� ������, ������� ��� ���������:

������������ ���:

>2013-01-28 00:38:51.863 BuilderPattern[708:11303] Phone Name = Low price phone!, osVersion = Android 2.3, cpu code name = Some shitty CPU, ram size = 256, os version code = 3, launcher = Hia Tsung!
>
>2013-01-28 00:38:51.867 BuilderPattern[708:11303] Phone Name = High price phone!, osVersion = Android 4.1, cpu code name = Some shitty but expensive CPU, ram size = 1024, os version code = 4.1, launcher = Samsung Launcher

[��� �������.][BuilderPattern]
 
## <a name="singleton"></a>Singleton

>//���������� ��������, ������� ����� ��������� ���, ������������� ������������� GCD � ARC.

��� ������ �� ��� ��������, ��� Singleton ����� �� ����� ������� ������� � iOS? ������, ��� ���� ������� ������. ����������, � .NET, ��������, ����������� ����� ����� �� �����, �� ���, � ��������, ���� ������ ������� � ����� ������� ������ ��������. � ������ ������, ��� ������� ����� - ������� � ������ ���������.

����, ������� ������ � �������� � � ��������.

Singleton - ��� ����� ������, ������� ���������� � ������� ������ � ������������ ����������. ����� ����� ������������ ��� �������� �����-�� ���������� ����������, �������� �������� ����������.

����, ��� � ��� � Obj-C ������ �� ����������� � �������� ����������:

``` objective-c
@interface SingletonObject : NSObject

@property (nonatomic, weak) NSString *tempProperty;
+(SingletonObject *) singleton;

@end
```

��� �����, ������� ������ � ����� ��������� � ����� �������. �����������, ������ �� ���������� �� �� ������� ����� ���� �������:

``` objective-c
@implementation SingletonObject

+(SingletonObject *) singleton
{
    static SingletonObject *singletonObject = nil;
    
    static dispatch_once_t onceToken;
    dispatch_once(&onceToken, ^{
        singletonObject = [[self alloc] init];
    });
    
    return singletonObject;
}
@end
```

����������, ��� � ��� :) iOS ��� �� ��� ����������� � ���, ����� ������ ��� ������ ���� ��������� ������ �������. ��� ����� ������� ��� ����� � ������� ��������, ������� �������� �������� ����� ������, ��� �����-����� ������ ������� � ��������:

1.	�����������, ��� ���� 2 ������.
2.	� ��� ������, ������������ ������� singleton. ����� �� � ������ ��������� ������ ���� ������, �� ������ ��� ��� ���������� � ���� ������ � ������ ������, ����� ��������� ��� �������. 

"�� ���� ����� ������� �������� �� nil!" � ������� ��.

� ������, ����������� ����� ������� ��������: ������� singleton �� ����������. ��� ������ ����� ��� ������� ������������:

1.	����� 1 ������ �������� ��� ������ ����������. �����, ��� ��� ���, � �������� ���� ��������.
2.	����� 2 ������ �������� �� ������������� �������, � ���� � ����� 1 �������� ��� ������, �� ������ ��� �� ����������.

��� ������� ����� �������, � .NET ������������ locks � ������������ ����, ��� ������ �������, ���� �� ����������� � ����� � ���� ������. ����������, dispatch_once ������ ���� ����� � �� ������ ���������� :) ������, �� ���� ����� �� ����� ����� � ���� ���, ���� �� �����.

����������, ��� GCD ����� ������� ���� �����, ����� ��� ��� �� �������� ��������� �������:

``` objective-c
+(SingletonObject *) singleton
{
    static SingletonObject *singletonObject = nil;
    @synchronized(self)
    {
        if (singletonObject == nil)
        {
            singletonObject = [[self alloc] init];
        }
    }

    return singletonObject;
}
```

��������� �� �� �����. ������������, ��� dispatch_once() �� ������������ ������� :) �� � ������������ ����� ����������.

����� ������ ������� �� ��������, � ������� ������:

``` objective-c
#define DEFINE_SHARED_INSTANCE_USING_BLOCK(block) \
static dispatch_once_t pred = 0; \
__strong static id _sharedObject = nil; \
dispatch_once(&pred, ^{ \
_sharedObject = block(); \
}); \
return _sharedObject; \
```

����� ���� ���������� �������� ������� ����� ��������� ��������� �������:

``` objective-c
+(SingletonObject *) singleton
{
    DEFINE_SHARED_INSTANCE_USING_BLOCK(^{
        return [[self alloc] init];
    });
}
```

��, � ������������� �������:

``` objective-c
[[SingletonObject singleton] setTempProperty:@"Hello 2 You!"];
NSLog(@"%@", [[SingletonObject singleton] tempProperty]);
```

[��� �������.][SingletonPattern]

## <a name="adapter"></a>Adapter
������ ����� ����� ��������� �������� �������� �������, ��� ������ �� ����� �������, ��� ������� ������� �� ���. �������! ��� ������ �� ������� ���������� ������� �����? �� ���, � ��� ������� � ����������� �������, � ������ - � ��������, � � ��������� ������� - ������ � ������������. �������������, ������ ����� �� �������� �����������, � ������ ����������� ������� ���� ���������.

�����������, ��� �� ����� � ������������ � ���. � ��� ����, ��������, ������� ��������� � ������ � ������������� ����� �� ������� �� ����� ������� ����� ������� ���������. ��� ������? �������� ������� ��� ������������� ���� �������? � ����� �� ��������� ����� � ��� ����� ������ � ��� ������� ������?

������, ��������� �����, �� ����������� ���� �� ���������, ������� ���������� �� �����, � ������� ��������� ��� ������������ ������ ������� � ���������� �� ���������� ������ �������.

��� � � ��������� � �� ��������� ��������� ������ �� �����, ������� ���������.

��� ������� ������� �� ���� ������: ���� (target), �������� (adapter), � ������������� (adaptee). 

� ����� � ���� ��������:

1.	Target � ������� �� ������ ��������
2.	Adapter � ����������. 
3.	Adaptee � ������� � ����������� �������.

������������� �������� ������� � Objective-C ����� ���� 2 (�������� ���� ������, �� � ���� ���):

����, ������ � ��� ����������� �������������. ����� � ��� ���� ������ Bird, ������� ��������� �������� BirdProtocol:

``` objective-c
@protocol BirdProtocol
-(void) sing;
-(void) fly;
@end


@interface Bird : NSObject <BirdProtocol>

@end
//����������
@implementation Bird

-(void) sing
{
    NSLog(@"Tew-tew-tew");
}

-(void) fly
{
    NSLog(@"OMG! I am flying!");    
}
@end
```

� ����� � ��� ���� ������ Raven, � �������� ���� ���� ���������:

``` objective-c
@interface Raven : NSObject

-(void) flySearchAndDestroy;
-(void) voice;

@end 

@implementation Raven

-(void) flySearchAndDestroy
{
    NSLog(@"I am flying and seak for killing!");
}

-(void) voice
{
    NSLog(@"Kaaaar-kaaaaar-kaaaaaaar!");
}
@end
```

����� ������������ ������ � �������, ������� ���� ����� :), ����� ������� ��� ���������� �������:

``` objective-c
@interface RavenAdapter : NSObject <BirdProtocol>
{
    @private Raven *_raven;
}

@property (nonatomic, strong) Raven *raven;

-(id) initWithRaven:(Raven*) adaptee;
@end 

//�� � ���� ����������. ��� ����� �� ��������� ������ � ������� ���������� BirdProtocol
@implementation RavenAdapter

@synthesize raven = _raven;

-(id) initWithRaven:(Raven*) adaptee
{
    self = [super self];
    _raven = adaptee;
    return self;
}

-(void) sing
{
    [_raven voice ];
}

-(void) fly
{
    [_raven flySearchAndDestroy];
}

@end
```

�� � ������� �� ����:

``` objective-c
-(void) makeTheBirdTest:(id<BirdProtocol>)aBird
{
    [aBird fly];
    [aBird sing];
}
//� �������� ���:

Bird *simpleBird = [[Bird alloc] init];
    
Raven *simpleRaven = [[Raven alloc] init];
    
RavenAdapter *ravenAdapter = [[RavenAdapter alloc] initWithRaven:simpleRaven];
    
[self makeTheBirdTest:simpleBird];
[self makeTheBirdTest:ravenAdapter];
```

��������� ����� ����� ������� � ����:

>2013-02-03 15:43:14.447 AdapterPattern[5985:11303] OMG! I am flying!
>
>2013-02-03 15:43:14.449 AdapterPattern[5985:11303] Tew-tew-tew
>
>2013-02-03 15:43:14.449 AdapterPattern[5985:11303] I am flying and seak for killing!
>
>2013-02-03 15:43:14.450 AdapterPattern[5985:11303] Kaaaar-kaaaaar-kaaaaaaar!

������ ����� ������� ����������, ������� ��� ��� ������� �� ����������, �� ��� ���������� ���������. �������� � ������ ����������� �������� � �������:

�������� � ��� ���� ������� ����� Charger:

``` objective-c
@interface Charger : NSObject
-(void) charge;
@end 

@implementation Charger

-(void) charge
{
    NSLog(@"C'mon I am charging");
}
@end
```

� ���� �������� ��� ����������� �������:

``` objective-c
@protocol EuropeanNotebookChargerDelegate
-(void) chargetNotebookRoundHoles:(Charger *)charger;
@end
```

���� ������� ������ ����������, �� ��������� �� �� �����, ��� � � ������� ������� :) ������, ������� ������� �������:

``` objective-c
@interface EuropeanNotebookCharger : Charger <EuropeanNotebookChargerDelegate>
{
    @private id<EuropeanNotebookChargerDelegate> _delegate;
}

@property (nonatomic, strong) id<EuropeanNotebookChargerDelegate> delegate;
@end
 
//����������
@implementation EuropeanNotebookCharger 

@synthesize delegate = _delegate;

-(id) init
{
    self = [super self];
    self.delegate = self;
    return self;
}

-(void) charge
{
    [_delegate chargetNotebookRoundHoles:self];
    [super charge];
}

-(void) chargetNotebookRoundHoles:(Charger *)charger
{
    //and yeah you can do smth with charger.
    NSLog(@"Charging with 220 and round holes!");
}

@end
```

��� �����, � ������ ������ ���� ��������, ������� ��������� ��� `EuropeanNotebookChargerDelegate`. ��� ���, ��� ����� ���� �������� ���������, �� ����� �������� ��������� ����, ������, ����� ���������� �����

``` objective-c
[_delegate chargetNotebookRoundHoles:self];
```

������ ���������� ���� �� �����. �� ������� ������, ��� ���� ��� �������.
������, ������� ������, ��� � �� ����� ����� � ������������ �������:

``` objective-c
@interface USANotebookCharger : NSObject
-(void) chargeNotebookRectHoles:(Charger *) charger;
@end
 
@implementation USANotebookCharger

-(void) chargeNotebookRectHoles:(Charger *) charger;
{
    NSLog(@"Charge Notebook Rect Holes");
}
@end
```

��� �����, � ������������ ������� ������ ������ ����� � �������������. ������� �������� ������� ��� �������:

``` objective-c
@interface USANotebookEuropeanAdapter : Charger <EuropeanNotebookChargerDelegate>

@property (nonatomic, strong) USANotebookCharger *usaCharger;

-(id) initWithUSANotebookCharger:(USANotebookCharger *) charger;

-(void) charge;
@end 

@implementation USANotebookEuropeanAdapter

-(id) initWithUSANotebookCharger:(USANotebookCharger *) charger
{
    self = [super init];
    self.usaCharger = charger;
    
    return self;
}

-(void) chargetNotebookRoundHoles:(Charger *) charger
{
    [self.usaCharger chargeNotebookRectHoles:charger];
}

-(void) charge
{
    EuropeanNotebookCharger *euroCharge = [[EuropeanNotebookCharger alloc] init];
    euroCharge.delegate = self;
    [euroCharge charge];
}
@end
```

��� �����, ��� ������ ��������� ��������� EuropeanNotebookChargerDelegate � ��� ����� chargetNotebookRoundHoles. ������, ����� ���������� ����� charge � �� ����� ���� ��������� ��� ����������� �������, �� ������������� ��� ������� ��� �������, � ���������� �� ����� charge. ��� ��� ��������� �������� ��� �������, ��� ������ ������ chargetNotebookRoundHoles, ����� ������� ���� ����� ������ ��������, �������, � ���� �������, �������� ����� ������� ���:)

������� ��������� ���� ��� � ����� ����:

``` objective-c
//��� �����
-(void) makeTheNotebookCharge:(Charger *) aCharger
{
    [aCharger charge];
}

//���� ���
EuropeanNotebookCharger *euroCharger = [[EuropeanNotebookCharger alloc] init];
    
[self makeTheNotebookCharge:euroCharger];
    
USANotebookCharger *charger = [[USANotebookCharger alloc] init];
USANotebookEuropeanAdapter *adapter = 
	[[USANotebookEuropeanAdapter alloc] initWithUSANotebookCharger:charger];
[self makeTheNotebookCharge:adapter];
```

��� ��� �������:

>2013-02-03 15:57:42.624 AdapterPattern[6179:11303] Charging with 220 and round holes!
>
>2013-02-03 15:57:42.626 AdapterPattern[6179:11303] C�mon I am charging
>
>2013-02-03 15:57:42.626 AdapterPattern[6179:11303] Charge Notebook Rect Holes
>
>2013-02-03 15:57:42.627 AdapterPattern[6179:11303] C�mon I am charging

[��� �������.][AdapterPattern]

## <a name="bridge"></a>Bridge

����������� ����, ��� � ��� ���� ���-�� ����������, � �������, � ��� ���� ������� � ���� ���������. ���� �� � ������� �������� ��� ���� ������, �� �� ����� �� ������������ ������ ����� ����� ���������. �� ��� �������! ���������� �� �� ����� � � ���������. ��� ����� �������� ��������� ����, ����� ��������� �������������� �������, �� �������� �� ���� � ������ ��������:) � ������, ��� �� ������ ������� ������� � ��� ���������� (� �� ������ ��� ��������� ��������� ��������:) ).

����������, ���� (Bridge) ��������� ��������� ���������� �� ����������, ��� ����� ���������� � ����� ������ ����� ���� ��������, �� ����� ��� ���� ����������.

����� ������������?

1.	��� ���������� �� ����� ����� ����� ����������� � �����������.
2.	����������, ��� ���������� ��� � ������������� ����� ����������� ����������.
3.	�� �� ������, ����� ��������� � ���������� ����� ������� �� ���������� ���.

������� �������� ������ ������� ���������� ���������:

``` objective-c
@interface BaseHeadphones : NSObject

-(void) playSimpleSound;
-(void) playBassSound;

@end
```
	
� ������ ��� �������� � ������� �������� � ������� :)

``` objective-c
//�������� ������� - ���������
@interface CheapHeadphones : BaseHeadphones

@end 

@implementation CheapHeadphones

-(void) playSimpleSound
{
    NSLog(@"beep - beep - bhhhrhrhrep");
}

-(void) playBassSound
{
    NSLog(@"puf - puf - pufhrrr");
}

@end 

//�������� �������, ���� ���������
@interface ExpensiveHeadphones : BaseHeadphones
@end
 
@implementation ExpensiveHeadphones

-(void) playSimpleSound
{
    NSLog(@"Beep-Beep-Beep Taram - Rararam");
}

-(void) playBassSound
{
    NSLog(@"Bam-Bam-Bam");
}

@end
```

� ���������� �����, ����� ������� �� ����� ������� ������:

``` objective-c
@interface MusicPlayer : NSObject

@property (nonatomic, strong) BaseHeadphones *headPhones;

-(void) playMusic;

@end
 
@implementation MusicPlayer

-(void) playMusic
{
    [self.headPhones playBassSound];
    [self.headPhones playBassSound];
    [self.headPhones playSimpleSound];
    [self.headPhones playSimpleSound];
    
}
@end
```

��� ������, ���� �� ������� ������ ������ � ��������. �� ����� ��������� � ����� ������, ��� ��� �������� ���� �� ����, �� �������� ���� ������� � ������� �������� �����������.
����!

``` objective-c
MusicPlayer *p = [[MusicPlayer alloc] init];
CheapHeadphones *ch = [[CheapHeadphones alloc] init];
ExpensiveHeadphones *ep = [[ExpensiveHeadphones alloc] init];
p.headPhones = ch;
[p playMusic];
p.headPhones = ep;
[p playMusic];
```

� ������� �� log:

>2013-02-06 23:03:52.378 BridgePattern[3397:c07] puf � puf � pufhrrr
>
>2013-02-06 23:03:52.379 BridgePattern[3397:c07] puf � puf � pufhrrr
>
>2013-02-06 23:03:52.380 BridgePattern[3397:c07] beep � beep � bhhhrhrhrep
>
>2013-02-06 23:03:52.380 BridgePattern[3397:c07] beep � beep � bhhhrhrhrep
>
>2013-02-06 23:03:52.380 BridgePattern[3397:c07] Bam-Bam-Bam
>
>2013-02-06 23:03:52.381 BridgePattern[3397:c07] Bam-Bam-Bam
>
>2013-02-06 23:03:52.381 BridgePattern[3397:c07] Beep-Beep-Beep Taram � Rararam
>
>2013-02-06 23:03:52.381 BridgePattern[3397:c07] Beep-Beep-Beep Taram � Rararam

[��� �������.][BridgePattern]

## <a name="facade"></a>Facade

������ ������� ������� ������� �� �������� ���� ���������. ��� �� � � �����, ����� ����� ��� ���������� ������ ��������� ��������, �� ������ ��������� ����� ���������. 

� �������, ����� ����� � ���� ��� ����:

1.	���������� ���������� �������, ������� �����, ���������� ����� ���� ������, ���������� ����� � ��� ���� �����.
2.	���������� ������ �����, ��� ����� ������ ����� ��������, ��������� ���, ��������� ������ �����, ����������� �����.
3.	�������� � ���������, ����������� ������, ������ �������, ����� �����, ��������.

� ��� ��� ��� ����, ����� ������ ���������� �����, ������� ���, ����� ��������, �� ����������.

��� �� ������� ������ Amazon � ������� � ������ ����� � ��� ����� ������ ������������� � �������� �������? � �������� ����� ��������, � �������� ������ ������, �������� ������ �� ������, �������� ��� �������� �������� ������ ������ � ����� ����� ����� � ���������� ����� ����� �������� ������� ���������� ����� �� ������ �����.

��� ����� ��� �������� ��� ��������� ������� � ����� (Facade), ������� ������������� ��������������� ���������� � �������� ���������� ����������� �������, ���������� ���� ������� ���������� ������� ����� � �������������.

�������, ��������� ������� �������, ������� ��� ��������� � ������ ����� ���� � ������ ������� ������! � ������ ��� ����� �������, ������� �������� ���� �� ������ ����� ����������� � ����� ����������:

``` objective-c
@interface PathFinder : NSObject

-(void) findCurrentLocation;
-(void) findLocationToTravel:(NSString *) location;
-(void) makeARoute;

@end 

@implementation PathFinder

-(void) findCurrentLocation
{
    NSLog(@"Finding your location. Hmmm, here you are!");
}

-(void) findLocationToTravel:(NSString *)location
{
    NSLog(@"So you wanna travell to %@", location);
}

-(void) makeARoute
{
    NSLog(@"Okay, to travell to this location we are using google maps....");
    //looking for path in google maps.
}
@end
```

����������� ��� ���������� ���� ������� ������ ���������� � ���������� �����������:

``` objective-c
@interface TravellEngine : NSObject

-(void) findTransport;
-(void) orderTransport;
-(void) travel;

@end
 
@implementation TravellEngine

-(void) findTransport
{
    NSLog(@"Okay, to travell there you will probabply need dragon!Arghhhhh");
}

-(void) orderTransport
{
    NSLog(@"Maaaam, can I order a dragon?... Yes... Yes, green one... Yes, with fire!... No, not a dragon of death... Thank you!");
}

-(void) travel
{
    NSLog(@"Maaan, you are flying on dragon!");
}

@end
```

�� � ����� �� ����������� ��� ��������:

``` objective-c
@interface TicketPrinitingSystem : NSObject

-(void) createTicket;
-(void) printingTicket;

@end

@implementation TicketPrinitingSystem

-(void) createTicket
{
    NSLog(@"Connecting to our ticketing system...");
}

-(void) printingTicket
{
    NSLog(@"Hmmm, ticket for travelling on the green dragon.Interesting...");
}

@end
```

� ������, ������� �������� ������ ������ �� ���� ���� ��������:

``` objective-c
@interface TravellSystemFacade : NSObject

-(void) travellTo:(NSString *)location;

@end 

@implementation TravellSystemFacade

-(void) travellTo:(NSString *)location
{

    PathFinder *pf = [[PathFinder alloc] init];
    TravellEngine *te = [[TravellEngine alloc] init];
    TicketPrinitingSystem *tp = [[TicketPrinitingSystem alloc] init];
    
    
    [pf findCurrentLocation];
    [pf findLocationToTravel:location];
    [pf makeARoute];
    
    [te findTransport];
    [te orderTransport];
    [tp createTicket];
    [tp printingTicket];
    [te travel];
}

@end
```

��� �����, ��� ����� ����� ��� ��� ��� �������, ������ � ����� ������ �� ����� � �������������� ��� ���� �������. ��� ����� �����������:

``` objective-c
TravellSystemFacade *facade = [[TravellSystemFacade alloc] init];
[facade travellTo:@"Lviv"];
```

������� ��������� ���:

>2013-02-09 17:46:28.442 FacadePattern[2410:c07] Finding your location. Hmmm, here you are!
>
>2013-02-09 17:46:28.444 FacadePattern[2410:c07] So you wanna travell to Lviv
>
>2013-02-09 17:46:28.445 FacadePattern[2410:c07] Okay, to travell to this location we are using google maps�.
>
>2013-02-09 17:46:28.446 FacadePattern[2410:c07] Okay, to travell there you will probabply need dragon!Arghhhhh
>
>2013-02-09 17:46:28.446 FacadePattern[2410:c07] Maaaam, can I order a dragon?� Yes� Yes, green one� Yes, with fire!� No, not a dragon of death� Thank you!
>
>2013-02-09 17:46:28.447 FacadePattern[2410:c07] Connecting to our ticketing system�
>
>2013-02-09 17:46:28.447 FacadePattern[2410:c07] Hmmm, ticket for travelling on the green dragon.Interesting�
>
>2013-02-09 17:46:28.448 FacadePattern[2410:c07] Maaan, you are flying on dragon!

[��� �������.][FacadePattern]

## <a name="mediator"></a>Mediator
�������� � �������, ������� ���������� ������ ���� ������, � ������� ����������� �������������� ����� ��������� ����������� ��������. ��� ���� ��� �������, ����� ���� �� ����� ��� ������������� ���� �����, ������ ��������������, ������������� � ���������, ����� ���� �������� ����������.

#### ����� ����� ������������:

1.	����� � ��� ���� ��������� ���������� ��������, � ����� ������ ����������� �������������� ����� ����. ����� ������ � ����� ���. ���������� ���� �������� ��������, � ��������� ���������. � �������, ������ ����������� ������ �� ���, ����� �� ������ ������ �����������, � ����������� ����� ��������� ������. ������ ����������� �� ����������� ����� � ������������� ������� �����������. ���� ����������� ���������, ������� �������� ������� �� ������� �� ��������� � ��������, ��� ������ � ��� ��� ���� ������.
2.	������ �������� ������������ ������, ��� ��� �� ��������������� � ������������� � �������� ����������� ������ ��������.
3.	������ �������������� ������ ����� ������������� � �����������.

����������, ������ ��������� ���� ������ ������������, ������ ��� ��� ����� ���������� ������� �� ���������� �� ����� ����� ����������. �������� ���� � �� view ���� ����� ����� ���������, � ��� ������� �������������� �� ����������� � �����������. �����������.

� ��� �� ������ �� ����� ������. ������� ��� �� �������� ������, ������� ���������� �������� �-�� ������ ����.

����� � ��� ���� ������������, ������� ����� ���������������� � ����� ����� �����:

``` objective-c
@class CentrallProcessor;

@interface SmartHousePart : NSObject
{
@private CentrallProcessor *_processor;
}

-(id) initWithCore:(CentrallProcessor *) processor;

-(void) numbersChanged;

@end
 
@implementation SmartHousePart

-(id) initWithCore:(CentrallProcessor *)processor
{
    self = [super init];
    _processor = processor;
    
    return self;
}

-(void) numbersChanged
{
    [_processor valueChanged:self];
}
@end
```

������, �������� ������ ������ ������ ����:

``` objective-c
@interface CentrallProcessor : NSObject

@property (nonatomic, weak) Thermometer *_thermometer;
@property (nonatomic, weak) ConditioningSystem *_condSystem;

-(void) valueChanged:(SmartHousePart *) aPart;

@end

@implementation CentrallProcessor

-(void) valueChanged:(SmartHousePart *) aPart
{
    NSLog(@"Value changed! We need to do smth!");
    
    //detecting that changes are done by thermometer
    if ( [aPart isKindOfClass:[Thermometer class]])
    {
        NSLog(@"Oh, the change is temperature");

        [[self _condSystem] startCondition];
    }
}

@end
```

��� ����� ���������� ������ � ����� `CentrallProcessor` ������ ����� ��� ������������� `SmartHousePart`, ���������� � `SmartHousePart` ������ ����� ��� ������������� `CentrallProcessor`. ���� ��� ������� ������� `import` � �� ������ �� ��������������. ������, � `SmartHousePart.h` �� ��������
`@class CentrallProcessor;` ��� ���� ����� XCode ����, ��� �� ������ ����� �����������, � ��� ���� �� �������� ���� ���������� `CentrallProcessor`.

��������� �� �� �������� � `SmartHousePart.m`.

������ � ������ `CentrallPart` � ������ `valueChanged` �� ����������, � ����� ������� � ��� ���������, ����� ��������� ������������. � ����� ������� � ��������� ����������� ������� � ����, ��� �� �������� �����������.

� ���, � ��� ���������� � ������������:

``` objective-c
@interface Thermometer : SmartHousePart

@property (nonatomic) int temperature;

-(void) temperatureChanged:(int) temperature;

@end

@implementation Thermometer

-(void)temperatureChanged:(int)temperature
{
    self.temperature = temperature;
    [self numbersChanged];
}

@end


@interface ConditioningSystem : SmartHousePart

-(void) startCondition;

@end

@implementation ConditioningSystem

-(void) startCondition
{
    NSLog(@"Conditioning...");
}

@end
```

��� �����, � ���������� � ��� ���� ��� �������, ������� ���� ��� ����� �� � �����, � ���-���� ��� ��������������� ���� � ������ ����������� ������ ��������� `CentrallProcessor`.

��� ��� ��������:

``` objective-c
CentrallProcessor *proccessor = [[CentrallProcessor alloc] init];
    
Thermometer *therm = [[Thermometer alloc] initWithCore:proccessor];
ConditioningSystem *condSystem = [[ConditioningSystem alloc] initWithCore:proccessor];
    
proccessor._condSystem = condSystem;
proccessor._thermometer = therm;
[therm temperatureChanged:45];
```

� ������� �� ���:

>2013-02-12 18:45:06.790 MediatorPattern[8809:c07] Value changed! We need to do smth!
>
>2013-02-12 18:45:06.793 MediatorPattern[8809:c07] Oh, the change is temperature
>
>2013-02-12 18:45:06.793 MediatorPattern[8809:c07] Conditioning�

[��� �������.][MediatorPattern]

## <a name="observer"></a>Observer

��� ����� ������� Observer? ��� �� �����-������ ������������� �� ������? �� ��������������, � ������ ���, ����� ������� ����� ����� ������, �� ��������� �� � ������ ����. �� ������ �� ������, ������ ����� ���������� ��� ����, � �����������, ������� ��������� ������, ���� �����, ���� � ����� ������ �������. ������ �������� ����� �������� � Publish � Subscriber.

��� ��������� ���� ������� ���� ������� GoF ����� � Observer ���������� ����-��-������ ��������� ����� ���������, � ���� ��������� ���������� � ������� � ��� ����������� �� ���� ������� ��� �� ������ ��� ��� ���������.

���� ������: ������, ������� �� �������� Subject, ���� ����������� ������ ��������, ������� ��������� ��������� Observer, ������������� � ������������ �� ���������, ������������ � Subject. ����� ��������� ���������� � ���� ���������������� �������� ���������� ���������, ��� ��������� ���������. � ����� ������ � Subject � ��� �������� ������, Observer - ��� �� � ���� � �� ��� ������������� �� ������, �� � ���������� ��������� � ��� ����� ����� ������, � ���������� � �������� ������ ���� �����������.

#### ����� ������������ �������:

1.	����� ��� ���������� �������� ���� ��������, ����������� �� ���������, ��� ��������� ���������, ��� ���� �� �� ������ ���� ���� ��������.
2.	��������� � ����� ������� �������, ����� ��������� ���������� � ������ ��������, ������ ���������� �������� ����� ���� ������.

���������� ����� �������� �������� ����� ���������:

#### 1. Notification

Notificaiton � �������� ������������� ������������ NotificationCenter ����� ������������ �������. ������������� NSNotificationCenter ��������� �������� ���������������, ���� �� ���� ���� ��� �����. ��� ����� ������ ������������, ����� � ��� � ������������ ������ ������ push-notification, ��� �� ���������� ����, � �� ������ ���� �� ���� ����� ��������� �� ������ ������ View.

����� ������� ����� ���������, ����� ������������ ����������� ����:

``` objective-c
NSNotification *broadCastMessage = [NSNotification
                    notificationWithName:@"broadcastMessage"
                    object:self];
NSNotificationCenter * notificationCenter = [NSNotificationCenter defaultCenter];
```

��� ����� �� ������� ������ ���� `NSNotification` � ������� �� ������� ��� ������ ����������: `�broadcastMessage�`, � ���������� �������� � ��� ����� `NotificationCenter`.

����� ����������� �� ������� � �������, ������� ������������� � ��������� ����� ������������ ��������� �����������:

``` objective-c
NSNotificationCenter * notificationCenter = [NSNotificationCenter defaultCenter];
[notificationCenter addObserver:self
                selector:@selector(update:)
                name:@"broadcastMessage" object:nil];
```

����������, �� ���� ��� �����-����� �������: �� ������������� �� �������, � ���������� ����� ������� ����� � �������� selector.

#### 2. ����������� �����.

����������� �����, ��� ���������� ����� �������� �����, ����� Subject ����� ��� ���� �����������, �� ��� ���� �� ����� �� ����. ������� ������ � ����, ��� �������� ��������� ��� Subject � Observer:

``` objective-c
@protocol StandardObserver <NSObject>

-(void) valueChanged:(NSString *)valueName newValue:(NSString *) newValue;

@end

@protocol StandardSubject <NSObject>

-(void) addObserver:(id<StandardObserver>) observer;
-(void) removeObserver:(id<StandardObserver>) observer;
-(void) notifyObjects;

@end
```

������, ������� �������� ���������� Subject:

``` objective-c
@interface StandardSubjectImplementation : NSObject <StandardSubject>
{
    @private NSString *_valueName;
    @private NSString *_newValue;
}

@property (nonatomic, strong) NSMutableSet *observerCollection;

-(void)changeValue:(NSString *)valueName andValue:(NSString *) newValue;

@end

@implementation StandardSubjectImplementation

-(NSMutableSet *) observerCollection
{
    if (_observerCollection == nil)
        _observerCollection = [[NSMutableSet alloc] init];
    
    return _observerCollection;
}


-(void) addObserver:(id<StandardObserver>)observer
{
    [self.observerCollection addObject:observer];
}

-(void) removeObserver:(id<StandardObserver>)observer
{
    [self.observerCollection removeObject:observer];
}

-(void) notifyObjects
{
    for (id<StandardObserver> observer in self.observerCollection) {
        [observer valueChanged: _valueName newValue:_newValue];
    }
}

-(void)changeValue:(NSString *)valueName andValue:(NSString *) newValue
{
    _newValue = newValue;
    _valueName = valueName;
    [self notifyObjects];
}

@end
```

�� � ���� �� ��� ����������:

``` objective-c
@interface SomeSubscriber : NSObject <StandardObserver>
@end

@implementation SomeSubscriber
-(void) valueChanged:(NSString *)valueName newValue:(NSString *)newValue
{
    NSLog(@"And some subscriber tells: Hmm, value %@ changed to %@", valueName, newValue);

}
@end

//� ������ ���������:
@interface OtherSubscriber : NSObject <StandardObserver>

@end

@implementation OtherSubscriber

-(void) valueChanged:(NSString *)valueName newValue:(NSString *)newValue
{
    NSLog(@"And some another subscriber tells: Hmm, value %@ changed to %@", valueName, newValue);
}

@end
```

���������� � ��� :) ������ ����-���:

``` objective-c
StandardSubjectImplementation *subj = [[StandardSubjectImplementation alloc] init];
SomeSubscriber *someSubscriber = [[SomeSubscriber alloc] init];
OtherSubscriber *otherSubscriber = [[OtherSubscriber alloc] init];

[subj addObserver:someSubscriber];
[subj addObserver: otherSubscriber];
[subj changeValue:@"strange value" andValue:@"newValue"];
```
� ����������� log:

>2013-02-16 17:31:43.176 ObserverPattern[24332:c07] And some subscriber tells: Hmm, value strange value changed to newValue
>
>2013-02-16 17:31:43.177 ObserverPattern[24332:c07] And some another subscriber tells: Hmm, value strange value changed to newValue

�� � ������� �� ��� ������������� KVO �������� �������� ��������� �� ��������.

���� �� ���� ����� ������� ������������ Obj-C � ��� key-value coding. ��� ���� ����� ����� �������� � ����������� ������������, �� ���� ��������� �� �������� � �� ��� ����������� �������� �������� ������� ������� � ������� ������� � ������� ��������� ������ ���� �������� ��������. ��� ������ ����� ��� ����������� ���������:

``` objective-c
    kvoSubj.changeableProperty = @"new value";
    
    [kvoSubj setValue:@"new value" forKey:@"changeableProperty"];
```

����� �������� ���� ��� ������ � ��� ����� ����� ������������� �����������, ������� ���������� key-value observing. ����� ��, ��� ����� ������� � ������������, �� ���� ��������� �� ��������:) �� ��� ����������� ����������� �� ��������� ������ ��������, � ������ ������� ������� KV compilant, ����� ��������. �� ����� ���� ����� ��������� �� �������.

������� �������� ����� � ����� ���������, ������� �� ����� ������:

``` objective-c
@interface KVOSubject : NSObject

@property (nonatomic, strong) NSString *changeableProperty;

@end

@implementation KVOSubject

@end
```

� �������� ������ ������� ����� ������� ��������� �������� changeableProperty:

``` objective-c
@interface KVOObserver : NSObject
@end

@implementation KVOObserver

-(void) observeValueForKeyPath:(NSString *)keyPath ofObject:(id)object change:(NSDictionary *)change context:(void *)context
{
    NSLog(@"KVO: Value changed;");
}

@end
```

��� �����, ���� ����� ��������� ������ ���� �����: observeValueForKeyPath. ���� ����� ����� ������, ����� ���������� �������� �������, �� ������� �� ���������.

������ ����:

``` objective-c
KVOSubject *kvoSubj = [[KVOSubject alloc] init];
KVOObserver *kvoObserver = [[KVOObserver alloc] init];
    
[kvoSubj addObserver:kvoObserver forKeyPath:@"changeableProperty"
            options:NSKeyValueObservingOptionNew context:nil];
    
[kvoSubj setValue:@"new value" forKey:@"changeableProperty"];
    
//because kvoSubj will be deallocated after this functions ends we need to remove observer information.
[kvoSubj removeObserver:kvoObserver forKeyPath:@"changeableProperty"];
```

��� ����� �� �������, �� ��� ������� �� ������� �� ���������, ��������� ������� addObserver � ��� �������������, ��� ����� ��������� �� �����������, �� ����������� ������ �������� �� ����� ��������� � ��������� �����. ������ ������ �������� ��������, � ��� ��� �� ��� ��� ����������� �� ������� ������ � � ����� �� ������� ����������� � ������ �������, ����� ������ �� �����.
��� ������� ��� �� ����:

>2013-02-17 11:41:58.051 ObserverPattern[26689:c07] KVO: Value changed;
>
>2013-02-17 11:41:58.052 ObserverPattern[26689:c07] KVO: Value changed;

[��� �������.][ObserverPattern]

## <a name="composite"></a>Composite

�� ������������ ��� ����� � ����� ����� ����������� ��������? ������� ���������� �� ����� ��������, � ���������� ����������� ��������. �� ����, ����� �������� � ����� ������ ���������� ����������� ���������, ����� ��������� ������.

�� ����� �������� ��� ������ ��������� ����� ���� �������, � ���� ���� � 10 ����������. � ��� ���� ���� � ������� ����������, � ��� ����� ���� ���������� �� ��������� �� ����� ������ � ������ ������!

����� �����, � �� ���������� ����� ���� �����, ������� ����� ����� �������� � ����������� ���������. �������� � ������� ����������� UI: � ������ � ��� ���� View, � ��� ��������� Subview, � ������� ����� ���� ��� ������ View, ��� ��� ����� ����������. �� �� ����� ���������:)

������ ��� �������� ����� ����� ������, � ������ �� �����������, ������������ ������� � ��������.

����� ������������ ����� �������?

���������� ����� �� ��������� � ������������ ������ ������, ��� ������ ���������� �������� ������ ����� �������.

������� �������� ����� �������� ���������:

� ������ ������ ���� ���������, � ������� ��������� ��� ��������� �������. ��������� ����� ������� ��� ������ ���������� � ����� ������ ������, ��� � ������� ������� ������������ �� ��������� � ������ ������ ������. �������� �����������, ��� ���������� ������� ������ ����� ������� ��� ������ ����������, ��� � ������.

������� ������!

������ � �������� ��������� ��� ����� ��������:

``` objective-c
@protocol CompositeObjectProtocol <NSObject>

-(NSString *) getData;
-(void) addComponent:(id<CompositeObjectProtocol>)aComponent;

@end
```

�������� ������ �����:

``` objective-c
@interface LeafObject : NSObject <CompositeObjectProtocol>

@property (nonatomic, strong) NSString *leafValue;

@end

@implementation LeafObject

-(NSString *) getData
{
    return [[NSString alloc] initWithFormat:@"<%@/>",self.leafValue ];
}

-(void) addComponent:(id)aComponent
{
    NSLog(@"Can't add component. Sorry, man");
}

@end
```

��� �����, ��� ������ �� ����� ��������� ���� ����� (�� �� �� �� ���������:) ), � ����� ���������� ���� �������� � ������� ������ getData.

������ ��� ����� ��������� ���������:

``` objective-c
@interface Container : NSObject <CompositeObjectProtocol>

@property (nonatomic,strong) NSMutableArray *components;

@end

@implementation Container

-(NSMutableArray *) components
{
    if (_components == nil)
        _components = [[NSMutableArray alloc] init];
    
    return _components;
}

-(void) addComponent:(id<CompositeObjectProtocol>)aComponent
{
    [self.components addObject:aComponent];
}

-(NSString *) getData
{
    NSMutableString *valueToReturn = [[NSMutableString alloc] init];
    [valueToReturn appendString:@"<ContainerValues>"];
    
    for ( id<CompositeObjectProtocol> object in _components)
    {
        [valueToReturn appendString:[object getData]];
    }
    [valueToReturn appendString:@"</ContainerValues>"];
    
    return valueToReturn;

}

@end
```

��� �����, ��� ��������� ����� ��������� � ���� �����, ������� ����� ���� ��� ���� Container ��� � ���� LeafObject. ����� getData ��, ������ �� ���� �������� � ������� components, � �������� ��� �� ����� ����� � �����. ��� ���������� � ���.

������, ������� �� ������:

``` objective-c
    Container *rootContainer = [[Container alloc] init];
    LeafObject *object = [[LeafObject alloc] init];
    object.leafValue = @"level1 value";
    [rootContainer addComponent:object];
    
    Container *firstLevelContainer1 = [[Container alloc] init];
    LeafObject *object2 = [[LeafObject alloc] init];
    object2.leafValue = @"level2 value";
    [firstLevelContainer1 addComponent:object2];
    [rootContainer addComponent:firstLevelContainer1];
    
    Container *firstLevelContainer2 = [[Container alloc] init];
    LeafObject *object3 = [[LeafObject alloc] init];
    object3.leafValue = @"level2 value 2";
    [firstLevelContainer2 addComponent:object3];
    [rootContainer addComponent:firstLevelContainer2];
    
    
    NSLog(@"%@", rootContainer.getData);
```

� ������� �� ���:

>2013-02-17 13:04:09.470 CompositePattern[27392:c07]
>
><ContainerValues>
>
>	<level1 value/>
>
>	<ContainerValues>
>
>		<level2 value/>
>
>	</ContainerValues>
>
>	<ContainerValues>
>
>		<level2 value 2/>
>
>	</ContainerValues>
>
></ContainerValues>

[��� �������.][CompositePattern]
 
## <a name="iterator"></a>Iterator

� ��������� � ���, ����� �� ������ �� ����� ��������, ����� �������� ������ ��� �������� ������� ��������, � ��������� ��� ��� �� ����� ������� �������. � ��� ���������� ��������, ����� ������� ������ � ��� ������� ������� ������. ( ��� ������ ���� �� ����� Pro Objective-C Design Patterns for iOS. ) . � ��� ���� ���������, ������� �������� �� ������, ������ �� ������� �������� ������������ ��� ������, � ������� ����� ������� Coca-Cola. ����� �� ���������� �����, �� ��� ������� ��������� �� ��������. ������� ������, ������� cocaColaCollection.next. ��� ����������� ����� � ��������� � ��������.
������� �������� ��������� ��������������� ���������� � ��������� ��������, �� ����� ������, ��� �� ��� �� ���������.
��������� ��� ���� ���������� � ���������� � �������. ��� ����� �� ��������, ������� �������� � ��������, ��� ������� ����� ������, � ���������� �� ��� (������) ����������� ��������� �� ������� ���� ������ ���������. ���������� �������� � ��� ���������� ����� ����� ��������, ������� ������������� ��������� ������� ��� ������������.

��� ������� ���������, ������� ����:

1.	������ ����� ��� ������������� ���������, ���� ��� � ���� ������ ��������.
2.	��������� � ��������� ����������.
3.	����� ������������ ��������� ���������, ��� ��������� ���������� ��������.

��� ����������:

1.	������� ���������� ���������� � ������������� ���������. �� ������ ������� ��������� ���������.
2.	��������� ���� ������� � ��������� ����������
3.	��������� ����� ������ ��������� ���������, �� ������ ��� ���� ��� �������.

#### ����� ������������ ��������:

1. ��� ���������� ����������� � �������� ���������, ��� ���� ����� ������ ������������ ���������.
2. ��� ���� �������� ������� ��������� ���������� ��������� (��������� �������� � � ��� ��������� ����� ���� �����������)
3. ��� ���������� ���� ��������������� ��������� ��� ��������� �������� ��������.

����� ������� ������ �������� ���������, ��� ������������� ������ NSEnumerator:

``` objective-c
    NSEnumerator *enumerator = [internallArrayCollection objectEnumerator];
    NSString* element;
    
    while (element = [enumerator nextObject]) {
        NSLog(@"%@",element);
}
```

��� �����, �� ������ �������� � ������� `internallArrayCollection` ����� `objectEnumerator` � � �������� ����������� ��� ��������. ������ ����� �� ��������������, � ������������ ������� ���� `for`:

``` objective-c
    for (NSString *element in internallArrayCollection)
    {
        NSLog(@"%@",element);
	}
```

� �� ������, ��� ����� ��������� ��������� ������� ����� ��������� ��������� � ����� `for` (���� ��� ����), ������ ���� ������ ����� ������.
����� �� �������� ���������� �������� ��������� � ����� ���� �������� � ������� ������:

``` objective-c
    [internallArrayCollection enumerateObjectsUsingBlock:
     ^(id obj, NSUInteger idx, BOOL *stop) {
         if([obj localizedCaseInsensitiveCompare:@"Dima"] == NSOrderedSame)
         {
             NSLog(@"Dima has been found!");
             *stop = YES;
         }
     }];
```

������� ����� ������ � ���, ��� ��� �������� �������� ����� �������� ������ �����������, ��� �� ���������� ����� ������ ������������ ����, ���������� ���� �������������. ��� �������� �������������� ���:

``` objective-c
    //�������� ����� ������ Dima � ������� �������
    void (^simpleDimaSearchBlock)(id, NSUInteger, BOOL*) =
    ^(id obj, NSUInteger idx, BOOL *stop){
        if([obj localizedCaseInsensitiveCompare:@"Dima"] == NSOrderedSame)
        {
            NSLog(@"Dima has been found!");
            *stop = YES;
        }
    };
    
 
   [internallArrayCollection enumerateObjectsUsingBlock:simpleDimaSearchBlock];
```

������� ��:)

������ ������� �������� ���� ��������, � �� � ��� :) ����� � ��� ����� ��������� �������, ���� �� ��� ����� �������, ������ �� � ������. �������� ��� ���������, ������� ����� ������ �� ������ ����� �������. ����, ��� ������ ��� ����� �������:

``` objective-c
@interface ItemInShop : NSObject

@property (nonatomic, strong) NSString *name;
@property (nonatomic) BOOL isBroken;

-(id) initWithArgs:(NSString *)aName andQaulity:(BOOL)isBroken;

@end

@implementation ItemInShop

-(id) initWithArgs:(NSString *)aName andQaulity:(BOOL)isBroken
{
    self = [super init];
    self.name = aName;
    self.isBroken = isBroken;
    return self;
}

@end
```

��� �����, �� ����� � ��� ��������, � �������������.
������ ������� �������� �����, � ������� ���������� ������ �� � �����:

``` objective-c
@interface ShopWarehouse : NSObject
{
    @private NSMutableArray *goods;
    @private GoodItemsEnumerator *goodItemsEnumerator;
    @private BadItemsEnumerator *badItemsEnumerator;
}


-(void) addItem:(ItemInShop *)anItem;

-(NSEnumerator *) getBrokenItemsEnumerator;
-(NSEnumerator *) getGoodItemsEnumerator;

@end

@implementation ShopWarehouse

-(id) init
{
    self = [super init];
    
    goods = [[NSMutableArray alloc] init];
    
    return self;
}

-(void) addItem:(ItemInShop *)anItem
{
    [goods addObject:anItem];
}

-(NSEnumerator *) getBrokenItemsEnumerator
{
    badItemsEnumerator = [[BadItemsEnumerator alloc] initWithItems:goods];
    return badItemsEnumerator;
}

-(NSEnumerator *) getGoodItemsEnumerator
{
    goodItemsEnumerator = [[GoodItemsEnumerator alloc] initWithItems:goods];
    return goodItemsEnumerator;
}

@end
```

��� �����, ��� ����� ����� ��������� ������, � ����� ���������� ��� ������������ ������� ��� ��������� GoodItemsEnumerator � BadItemsIterator. ����������, �� ���������� ��������, ������� ��������� �� ����������. ��� ������ �������� ������� ����� ��� �����:

``` objective-c
@interface BasicEnumerator : NSEnumerator
-(id)initWithItems:(NSMutableArray *)anItems;
-(NSArray *)allObjects;
-(id) nextObject;
@end
```

��� �����, ��� ������ ���������, ������� ������������ ���������� 3� �������: �������������, ������� ��� ������� � ������� ��������� ������. ������� �������� ��� ���������, ��� � ������������:

``` objective-c
@interface BadItemsEnumerator : BasicEnumerator
{
    @private NSMutableArray *itemsArray;
    @private NSEnumerator *internalEnumerator;
}
@end

@implementation BadItemsEnumerator
-(id) initWithItems:(NSMutableArray *)anItems
{
    self = [super init];
    itemsArray = [[NSMutableArray alloc] init];
    for ( ItemInShop *item in anItems)
    {
        if (item.isBroken)
            [itemsArray addObject:item];
    }
    internalEnumerator = [itemsArray objectEnumerator];
    
    return self;
}

-(NSArray *)allObjects
{
    return itemsArray;
}

-(id) nextObject
{
    return [internalEnumerator nextObject];
}

@end
```

� �� ������� ��� 'GoodItemsIterator', ������ ��� ��������� ��� ����� ������ � ����� �������:

``` objective-c
if (!item.isBroken)
```

��� �����, �� ����� ������������� �� ������� ���� ����� ������, � ������� ������ ������ ������. ��� �� ������� ���� ���������� ��������, �� ����������� Cocoa.
�� ���, ������:

``` objective-c
//�������� �������� �����
    shopWarehouse = [[ShopWarehouse alloc] init];
    
    [shopWarehouse addItem:[[ItemInShop alloc]initWithArgs:@"Item1" andQaulity:NO]];
    [shopWarehouse addItem:[[ItemInShop alloc]initWithArgs:@"Item2" andQaulity:NO]];
    [shopWarehouse addItem:[[ItemInShop alloc]initWithArgs:@"Item3" andQaulity:YES]];
    [shopWarehouse addItem:[[ItemInShop alloc]initWithArgs:@"Item4" andQaulity:YES]];
    [shopWarehouse addItem:[[ItemInShop alloc]initWithArgs:@"Item5" andQaulity:NO]];
```

��� ����:

``` objective-c
    GoodItemsEnumerator *goodIterator = [shopWarehouse getGoodItemsEnumerator];
    BadItemsEnumerator *badIterator = [shopWarehouse getBrokenItemsEnumerator];
    
    ItemInShop *element;
    while (element = [goodIterator nextObject]) {
        NSLog(@"Good Item = %@", element.name);
    }
    
    while (element = [badIterator nextObject]) {
        NSLog(@"Bad Item = %@", element.name);
```

� ������� �� ���:
>2013-02-25 01:18:10.401 IteratorPattern[5000:c07] Good Item = Item1
>
>2013-02-25 01:18:10.403 IteratorPattern[5000:c07] Good Item = Item2
>
>2013-02-25 01:18:10.403 IteratorPattern[5000:c07] Good Item = Item5
>
>2013-02-25 01:18:10.404 IteratorPattern[5000:c07] Bad Item = Item3
>
>2013-02-25 01:18:10.405 IteratorPattern[5000:c07] Bad Item = Item4

[��� �������.][IteratorPattern]
 
## <a name="visitor"></a>Visitor

��� � ������� ���� ��������� ����� ���� �����������. � ����� ����, ��� �����������. ��� �����, ���� ����������� ���������? ��������� ������, �������� � ��������� ��� ������ �����������, ����� ������, ��������� ����������� ��� ���, � ��������������� ������� ������� �� ������� �������������. �������� � ����������� ���, �� ������� ������� ����������� ��������� ���������� ������ �������, ��� �������� �� ������ �� ������, � �������� � ������� �������.
������� ������� � ��������� ������� �� ����� �������� ������, ������� ��������� � ���� ��������, � ��������� �����, ��� ��������� ��� ����� �������� / ��������� ���������, ��� ���� �� ����� ������ ������ ������.

#### ����� �� ������� ������������ ���� �������:

1.	����� � ��� ���� ������� ������, � ������� ���������� ������� ���������� ��������� ���������, � �� ������ ��������� ��������� �������� � ����������� �� ���� ���� ���������.
2.	��� ���������� ��������� ��������� �������� ��� �������, � ��� ���� �� �� ������ ������ ����� ���� ������ ���������� ���� �������.
3.	� ����� ������, ��� ����� ��������� ��������� �������� ��� ����������, � �� �� ������ ��������� ��������� ������ ���� ���������.

����, ������� �������� � ������� �� ������� ������, ������ ������ ������� � � ��� ���� ��������� �������, � ������ ������ ����� ��������� �����. ���� ������� ����� �������� ������, ������ ������� ����� �������� ���� ������ � ������.

����, ��� ������ ��� �����:

``` objective-c
@interface WarehouseItem : NSObject

@property (nonatomic, strong) NSString *name;
@property (nonatomic) BOOL isBroken;
@property (nonatomic) int price;


-(id) initWithArgs:(NSString *)aName andQuality:(BOOL) isBrokenState andPrice:(int)aPrice;

@end

@implementation WarehouseItem

-(id) initWithArgs:(NSString *)aName andQuality:(BOOL)isBrokenState andPrice:(int)aPrice
{
    self = [super init];
    self.name = aName;
    self.isBroken = isBrokenState;
    self.price = aPrice;
    return self;
}
@end
```

� ����������� ��� �����:

``` objective-c
@interface Warehouse : NSObject
{
@private NSMutableArray *_itemsArray;
}

-(void) addItem:(WarehouseItem *) anItem;
-(void) accept:(id<BasicVisitor>) visitor;

@end

@implementation Warehouse
-(void) addItem:(WarehouseItem *)anItem
{
    if (!_itemsArray)
        _itemsArray = [[NSMutableArray alloc] init];
    
    
    [_itemsArray addObject:anItem];
}

-(void) accept:(id<BasicVisitor>) visitor
{
    [visitor visit:self];
    for (WarehouseItem *item in _itemsArray)
        [visitor visit:item];
}

@end
```

��� �����, ��� ����� ����� ������� � ��������� �����, �� ����� �������� ������������ ������� accept, ������� ��������� � ���� ������� � ������� ��� ����� visit. ����� �������� ���������, ������� �������� �������� BasicVisitor � ��������� ���������:

``` objective-c
@protocol BasicVisitor <NSObject>

-(void) visit:(id)anObject;

@end
```

��� �����, �������� ������� ���������� ������ ������ ������. ������ ������� �������� � ����� ���������:

``` objective-c
@interface QualityCheckerVisitor : NSObject <BasicVisitor>

@end
@implementation QualityCheckerVisitor

-(void) visit:(id)anObject
{
    if ([anObject isKindOfClass:[WarehouseItem class]])
    {
        if ([anObject isBroken])
        {
            NSLog(@"Item: %@ is broken", [anObject name]);
        }
        else
        {
            NSLog(@"Item: %@ is pretty cool!", [anObject name]);
        }
    }
    
    if ([anObject isKindOfClass:[Warehouse class]])
    {
        NSLog(@"Hmmm, nice warehouse!");
        return;
    }

}

@end
```

���� �������� ���, �� ����� �����, ��� ������� ��� ������ ������ ������ visit ���������� ��� �������, ������� ��� ���������, � ��������� ������������ ������� � ���������� �� ����� ����. ������ ������ ������ ������� ������ ��� �������� ���� �� ������, � ��� �� ��� ��� �������� �����:)

``` objective-c
@interface PriceCheckerVisitor : NSObject <BasicVisitor>

@end

@implementation PriceCheckerVisitor

-(void) visit:(id)anObject
{
    if ([anObject isKindOfClass:[WarehouseItem class]])
    {
        NSLog(@"Item: %@ have price = %i", [anObject name], [anObject price]);
    }
    
    if ([anObject isKindOfClass:[Warehouse class]])
    {
        NSLog(@"Hmmm, I don't know how much Warehouse costs!");
        return;
    }
    
}


@end
```

� �������� ���� ������� ������ �� �� �����, ������ � ������ ������ �� ����������, ��� ��������, � � ������ ������ ������� ���� ������!
������ ������� �������� ��, ��� � ��� ����������! ��� ��������� �������� �����:

``` objective-c
    _localWarehouse = [[Warehouse alloc] init];
    [_localWarehouse addItem:[[WarehouseItem alloc] initWithArgs:@"Item1" andQuality:NO andPrice:25]];
    [_localWarehouse addItem:[[WarehouseItem alloc] initWithArgs:@"Item2" andQuality:NO andPrice:32]];
    [_localWarehouse addItem:[[WarehouseItem alloc] initWithArgs:@"Item3" andQuality:YES andPrice:45]];
    [_localWarehouse addItem:[[WarehouseItem alloc] initWithArgs:@"Item4" andQuality:NO andPrice:33]];
    [_localWarehouse addItem:[[WarehouseItem alloc] initWithArgs:@"Item5" andQuality:NO andPrice:12]];
    [_localWarehouse addItem:[[WarehouseItem alloc] initWithArgs:@"Item6" andQuality:YES andPrice:78]];
    [_localWarehouse addItem:[[WarehouseItem alloc] initWithArgs:@"Item7" andQuality:YES andPrice:34]];
    [_localWarehouse addItem:[[WarehouseItem alloc] initWithArgs:@"Item8" andQuality:NO andPrice:51]];
    [_localWarehouse addItem:[[WarehouseItem alloc] initWithArgs:@"Item9" andQuality:NO andPrice:25]];
```

� ���������� ��� �������� ���:

``` objective-c
    PriceCheckerVisitor *visitor = [[PriceCheckerVisitor alloc] init];
    QualityCheckerVisitor *qualityVisitor = [[QualityCheckerVisitor alloc] init];
    
    [_localWarehouse accept:visitor];
    [_localWarehouse accept:qualityVisitor];
```

����, ��� ������ ������ accept ������ ������, ������� ������� ����������� ��� �����, � ����� ����������� ������ ����� �� ���� ������. ��� ���� �� ����� ������ ��� �������� ��� � ��������, � ��� �� �������� ��������� � ���� �������:)
������������ ���:

>2013-02-26 00:19:47.756 VisitorPattern[8748:c07] Hmmm, I don�t know how much Warehouse costs!
>
>2013-02-26 00:19:47.759 VisitorPattern[8748:c07] Item: Item1 have price = 25
>
>2013-02-26 00:19:47.759 VisitorPattern[8748:c07] Item: Item2 have price = 32
>
>2013-02-26 00:19:47.760 VisitorPattern[8748:c07] Item: Item3 have price = 45
>
>2013-02-26 00:19:47.761 VisitorPattern[8748:c07] Item: Item4 have price = 33
>
>2013-02-26 00:19:47.762 VisitorPattern[8748:c07] Item: Item5 have price = 12
>
>2013-02-26 00:19:47.763 VisitorPattern[8748:c07] Item: Item6 have price = 78
>
>2013-02-26 00:19:47.763 VisitorPattern[8748:c07] Item: Item7 have price = 34
>
>2013-02-26 00:19:47.764 VisitorPattern[8748:c07] Item: Item8 have price = 51
>
>2013-02-26 00:19:47.765 VisitorPattern[8748:c07] Item: Item9 have price = 25
>
>2013-02-26 00:19:47.765 VisitorPattern[8748:c07] Hmmm, nice warehouse!
>
>2013-02-26 00:19:47.766 VisitorPattern[8748:c07] Item: Item1 is pretty cool!
>
>2013-02-26 00:19:47.767 VisitorPattern[8748:c07] Item: Item2 is pretty cool!
>
>2013-02-26 00:19:47.767 VisitorPattern[8748:c07] Item: Item3 is broken
>
>2013-02-26 00:19:47.768 VisitorPattern[8748:c07] Item: Item4 is pretty cool!
>
>2013-02-26 00:19:47.769 VisitorPattern[8748:c07] Item: Item5 is pretty cool!
>
>2013-02-26 00:19:47.837 VisitorPattern[8748:c07] Item: Item6 is broken
>
>2013-02-26 00:19:47.837 VisitorPattern[8748:c07] Item: Item7 is broken
>
>2013-02-26 00:19:47.837 VisitorPattern[8748:c07] Item: Item8 is pretty cool!
>
>2013-02-26 00:19:47.838 VisitorPattern[8748:c07] Item: Item9 is pretty cool!

[��� �������.][VisitorPattern]
 
## <a name="decorator"></a>Decorator

>//��� ����� ���� ��� � ����� �������� ��� � �����, � ���� ����� � ������� ���������� � ������ ���� �������, ����� �� ����� ���� ������, ��� � ������� �������������� ������ ����� �������. � �� ������������� ����, ������ ��� ���������� ���������, ���� � ������������ ���������� ��� ��������� ������ ���� ��������� ��������. ������������ ���������� ����� ��������� �����

�������� ������ ���������� � ��������� ������� ��� ����� ���������. ���-�� � ����� � ����� �����:) ��� ������ � ��� ���� �������. �� ��� ��� ������� �������, �� ����� ����� ��������� ���� �� �� ���������� ��� ����� ������� � ������ �� �������� ����� ��� ����. �� ����, � ��� ������������� �������� �� �������� ���������� ������ �� �������. �� ��� �� ����� �������� ����� � ������ ��� ������� ��� � �������� �������. � ����� �� �������� ������� ��������, � ������� �������� ����� ������ ���������� � �������� �������� ������. ������������ ��� ������� �������������� ������������:)

���, �������������� ��� �������� ������� �������� �������� ���������. ������ �������� GoF:
��������� ��������� ����� ���������� ��� ������������� �������.

����� ������������ ���� �������:

1.	�� ������ �������� ������������� ������� �������������� �����������, ��� ���� �� ������� � �� ����� ������ ��������
2.	�������������� ����������� ������ � �����������

������� Objective-C � ����� ������ � ��� ������������� ���������. � �� ���� �������� ��������� ��������� � ���� �����, �� � ���� ������ ��� �� ��������:
��������� � ��� ����������� ��������� ����� ������ ��������������� �������� (������ ��������) ��� ������������� �� ����. ������� ������� ����� ������� ������ � ������������� Cocoa �������. � ������� ������� ����� ����� ��� ������� NSDate:

� �������, ��� ����� ����� ����������� ����� ���� � ����� ���������� ��� �� ����������� ��������������� � �������� � ���� �������. ��� ������ �������� ���������:

``` objective-c
@interface NSDate (StringDate)

-(NSString *) convertDateToString;

@end

@implementation NSDate (StringDate)

-(NSString *) convertDateToString
{
    NSDateFormatter *formatter = [[NSDateFormatter alloc] init];
    [formatter setDateFormat:@"yyyy/dd/MM"];
    
    return [formatter stringFromDate:self];
}

@end
```

��� ����� ���� ��������� ���������� ������ ���� ����� �convertDateToString�, ������� ���� ����������� � �����-�� ������ �������� ������, �� � ��� ����� ������:)
������ ����-������, ������� ��� ��������� ���������� ��� ���� �������� NSDate � ����� ����������. ��� ����� � ����� appName-Prefix, ��������� �������:

``` objective-c
#ifdef __OBJC__
    #import <UIKit/UIKit.h>
    #import <Foundation/Foundation.h>
    #import "NSDate+StringDate.h"
#endif
```

������� �������� ������, ����� �� ����������.

�� ������ ��������, �� � �������� ��� � ���:) ��������� ��� ������������ �������� ��������� �������:

``` objective-c
    NSDate *dateNow = [NSDate date];
    
    NSLog(@"Date is %@", [dateNow convertDateToString]);
```

������������ log:

>2013-03-01 00:30:18.328 DecoratorPattern[11731:c07] Date is 2013/01/03

[��� �������.][DecoratorPattern]

## <a name="cor"></a>Chain of responsibility

������� � ���� ������� ��������� :)

����������� ���� ������� �����, ������� ������ �� ���������. �������� ������� ������� ���� ������ ������� ������� � ������� ��������, �� ������� �� ���-������� �� ������, �����, ��� ������� �� ��� ����, � �������� ������� ������. ������ ������� ������ ���������� ���� �����, � ��� ���� �� �������� ����������.

������� ��������������� (chain of responsibility) � ��������� ��� ���������� ������ �� ������� ��������-������������, ���� �� ����� ������ ����������� ������-����������.

����� ������������ ���� �������:

1.	� ��� ����� ��� ���� ������-����������.
2.	� ��� ���� ��������� �������� �����������, ��� ���� �� �� ������ ��������������� ������� ������ ������ ������������ � ����� ������ �������.

��� ������ � ������:

����������, ��� � ��� ���� ��������, ������� ������������ ��������� ��������, ������� �� ���: �������, ����������� � ������.
��� ������ �������� ������ ��������, ������� ����� ���� ���������� ������ �������������:

``` objective-c
//������� ������
@interface BasicItem : NSObject
@end

@implementation BasicItem
@end

//�������
@interface Toy : BasicItem
@end

@implementation Toy
@end

//�����������
@interface Electronics : BasicItem
@end

@implementation Electronics
@end

//� �����
@interface Trash : BasicItem
@end

@implementation Trash
@end
```

������ �������� �����������:

``` objective-c
@interface BasicHandler : NSObject
{
@private BasicHandler *_nextHandler;
}

@property (nonatomic, strong) BasicHandler *nextHandler;
-(void) handleItem:(BasicItem *) item;
@end

@implementation BasicHandler
@end
```

��� �����, ��� ������� ����������, ����� ������������ ������� ���� BasicItem. � ����� ������ � �� ����� ������ �� ��������� ���������� (��� � ����� �������, ��� ����� ���������� �������).
������� �������� ��� ����������� �������:

``` objective-c
@interface ToysHandler : BasicHandler
@end

@implementation ToysHandler

-(void) handleItem:(BasicItem *)item
{
    if ([item isKindOfClass:[Toy class]])
    {
        NSLog(@"Toy found. Handling");
    }
    else
    {
        NSLog(@"Toy not found. Handling using next handler");
        [self.nextHandler handleItem:item];
    }
}

@end
```

��� �����, ���� ���������� �������� ������ ������ Toy � �� �� ��� ������������, ���� ��� � �� ���������� �������� ������ ���������� �����������.
�� �������� �������� ��� ��������� �����������: ��� �����������, � ������:

``` objective-c
//������� �����������
@interface ElectronicsHandler : BasicHandler
@end

@implementation ElectronicsHandler

-(void) handleItem:(BasicItem *)item
{
    if ([item isKindOfClass:[Electronics class]])
    {
        NSLog(@"Electronics found. Handling");
    }
    else
    {
        NSLog(@"Electronics not found. Handling using next handler");
        [self.nextHandler handleItem:item];
    }
}

@end


//������� ������
@interface OtherItemsHandler : BasicHandler
@end

@implementation OtherItemsHandler

-(void) handleItem:(BasicItem *)item
{
    NSLog(@"Found undefined item. Destroying");
}

@end
```
	
��� ����� OtherItemsHandler � ������, ����� �� ���� ����� ���� � ������ ����������, � �� ������� ������� ��������� ����������.

������� �����������:

``` objective-c
    BasicHandler *toysHandler = [[ToysHandler alloc] init];
    BasicHandler *electronicsHandler = [[ElectronicsHandler alloc] init];
    BasicHandler *otherItemHandler = [[OtherItemsHandler alloc]init];
    
    electronicsHandler.nextHandler = otherItemHandler;
    toysHandler.nextHandler = electronicsHandler;
    
    BasicItem *toy = [[Toy alloc] init];
    BasicItem *electronic = [[Electronics alloc] init];
    BasicItem *trash = [[Trash alloc] init];
    
    
    [toysHandler handleItem:toy];
    [toysHandler handleItem:electronic];
    [toysHandler handleItem:trash];
```

��� ����� �� � ������ ������� �����������, ����� ��������� �� � ����, � �������� ���������� ��������� ��������. ����������� ���:

>2013-03-02 15:35:35.668 ChainOfResponsibility[16777:c07] Toy found. Handling
>
>2013-03-02 15:35:35.671 ChainOfResponsibility[16777:c07] Toy not found. Handling using next handler
>
>2013-03-02 15:35:35.672 ChainOfResponsibility[16777:c07] Electronics found. Handling
>
>2013-03-02 15:35:35.673 ChainOfResponsibility[16777:c07] Toy not found. Handling using next handler
>
>2013-03-02 15:35:35.673 ChainOfResponsibility[16777:c07] Electronics not found. Handling using next handler
>
>2013-03-02 15:35:35.674 ChainOfResponsibility[16777:c07] Found undefined item. Destroying

[��� �������.][ChainOfResponsibility]
 
## <a name="templatemethod"></a>Template Method

�� �������� ��� ����� � ����� ����� ��������? �� � ������� � ���� ��������� ����� �� �������� � ���������� ���:

1.	�����
2.	������������� � ���������
3.	���������, ������ � ���, ��� � ��� ����� �� �������
4.	������, � ����� ��������� ����� �������/������/�������� ��������.

��� �� ����� �� �������� � ��������, ��� ���������� ������:

1.	�����
2.	������������� � ���������
3.	�� ����������, ������ ��� ������!
4.	������� ����� ������ �������� �������� ��� �������� ��� ������������� �����!

� �����, ��� ���������� ����������� ���������, �� � ��������� � ������ ��������� ������:) �������� ������ ��, ��� � ���������� �������� ���������.
��������� ����� ������ ��������� ���������� ����������. �������� ��������� ��, ������������ � ����������� �������.

��� ������� �� ����� �����������, � � ������, ��� ������ ����� ��� ������������ ���. ������ ������� ��������� ������� ������.
�������� � ������ ��������, ������ ������� �� �������� ���������!

����, ������� ��� ��������� �����, � ������� �������� ����� ��������� �������:

``` objective-c
@interface AnyPhoneTemplate : NSObject
//it will be template method
-(void) makePhone;
-(void) takeBox;
-(void) takeMicrophone;
-(void) takeCamera;
-(void) assemble;
@end

@implementation AnyPhoneTemplate
//our template method
-(void) makePhone
{
    [self takeBox];
    [self takeCamera];
    [self takeMicrophone];
    [self assemble];
}

-(void) takeBox
{
    NSLog(@"Taking a box");
}

-(void) takeCamera
{
    NSLog(@"Taking a camera");
}
-(void) takeMicrophone
{
    NSLog(@"Taking a microphone");
}

-(void) assemble
{
    NSLog(@"Assembling everythig");
}

@end
```

��� �� ��� �������� ���������� � ��� ��������� �����, ��� ����� makePhone � ������� ������ ������������������ ������� ������� ����������� ��� ����������� ���������. ������� ������ ������ ���� ��������� ��������� ������:

``` objective-c
@interface iPhoneMaker : AnyPhoneTemplate

-(void) design;

@end

@implementation iPhoneMaker

-(void) takeBox
{
    [self design];
    [super takeBox];
}


-(void) design
{
    NSLog(@"Putting label 'Designed in California'");
}
@end
```

��� �����, � �������� �������� ��������� ���� ���� �������������� ����� � design, � ����� ������������� ����� takeBox � ������� ������������� ���������� ����� design � ����� ����� ���������� ������������ ����� takeBox.

�� ������� ������ Android:

``` objective-c
@interface AndroidMaker : AnyPhoneTemplate

-(void) addRam;
-(void) addCPU;

@end

@implementation AndroidMaker

-(void) assemble
{
    [self addCPU];
    [self addRam];
    [super assemble];
}

-(void) addCPU
{
    NSLog(@"Installing 4 more CPUs");
}

-(void) addRam
{
    NSLog(@"Installing 2Gigs of RAM");

}

@end
```

��� �����, � �������� �������� �� ����� ��� �������������� ������, � ���������� ����� assemble.

���� ����� ������� �� � ������������:

``` objective-c
    AndroidMaker *android = [[AndroidMaker alloc] init];
    iPhoneMaker *iphone = [[iPhoneMaker alloc] init];
    
    
    [android makePhone];
    [iphone makePhone];
```

������������ log:

>2013-03-03 22:56:28.996 TemplateMethod[21040:c07] Taking a box
>
>2013-03-03 22:56:28.998 TemplateMethod[21040:c07] Taking a camera
>
>2013-03-03 22:56:28.999 TemplateMethod[21040:c07] Taking a microphone
>
>2013-03-03 22:56:29.000 TemplateMethod[21040:c07] Installing 4 more CPUs
>
>2013-03-03 22:56:29.000 TemplateMethod[21040:c07] Installing 2Gigs of RAM
>
>2013-03-03 22:56:29.001 TemplateMethod[21040:c07] Assembling everythig
>
>2013-03-03 22:56:29.001 TemplateMethod[21040:c07] Putting label �Designed in California�
>
>2013-03-03 22:56:29.002 TemplateMethod[21040:c07] Taking a box
>
>2013-03-03 22:56:29.003 TemplateMethod[21040:c07] Taking a camera
>
>2013-03-03 22:56:29.003 TemplateMethod[21040:c07] Taking a microphone
>
>2013-03-03 22:56:29.003 TemplateMethod[21040:c07] Assembling everything

[��� �������.][TemplateMethod]

## <a name="strategy"></a>Strategy

���� ���� ������� ����, �� ������ ����� ������ �������� � ��� ���������. ���� �� ����� ������� �����, �� ��������� ����� �� �� ������ ���������� � ������� �������� ������� ���� ��� �������� � ������������ ����. � ��������� ���������, � ��� ����� ���� ����� ������ ��������� ���������. � �������, � ���������� �� ������ ������������ ��������� ��������� ������, � ����������� �� ���� � ����� �������� �������� �� ���������, ��� �� ���� �� ������ ����� ����� �������� ����. ��� �� � ��������� �� �������� ���������.

����� �������� �������� ����� ���� MVC ������� � � ������ ������� �� ����� ������������ ������ ����������� ��� ������ � ���� �� View (� ������� ���������������� � �� ���������������� ������������).

������� ��������� ���������� ��������� ����������, ������� ����� ����������������.

����� ������������ �������:

1.	��� ���������� ��������� ���������
2.	�� ����� �� ������ ������������ ���� �������� if-��
3.	� ��������� ������� ��� ����� �������� ��-�������.

������� ������� ������ � RPG ����, � ������� � ��� ���� ��������� ��������� ��������� ������ �����������:) ������ ���, ����� �� ������� ���, ���� ��������� ������ ������������ ��������. ����, ��� ������ ���������� �����������! 

�������� ������� ���������:

``` objective-c
@interface BasicStrategy : NSObject
-(void) actionCharacter1;
-(void) actionCharacter2;
-(void) actionCharacter3;
@end
```

��� ����� �� ���� ��������� � � ��� ���� 3 ���������, ������ �� ������� ����� ��������� ���� ��������! ������� ������ ���������� ��������!

``` objective-c
@interface AttackStrategy : BasicStrategy
@end

@implementation AttackStrategy

-(void) actionCharacter1
{
    NSLog(@"Character 1: Attack all enemies!");
}

-(void) actionCharacter2
{
    NSLog(@"Character 2: Attack all enemies!");
}

-(void) actionCharacter3
{
    NSLog(@"Character 3: Attack all enemies!");
}
@end
```

��� �����, ��� ������������� ����� ��������� ���� ��������� �������� �� ���, ��� ��������! ������� ������ �� ����������:

``` objective-c
@interface DefenceStrategy : BasicStrategy

@end

@implementation DefenceStrategy

-(void) actionCharacter1
{
    NSLog(@"Character 1: Attack all enemies!");
}

-(void) actionCharacter2
{
    NSLog(@"Character 2: Healing Character 1!");
}

-(void) actionCharacter3
{
    NSLog(@"Character 3: Protecting Character 2!");
}
@end
```

��� �����, �� ����� �������� ���������, ���� ��������� ��������� ��-������� � ��� �������, ��� �����, � ��������� ���� ��������:) ��, ������ ���-�� ���� ��� ��� ������������. ������� �������� ������ ������:

``` objective-c
@interface Player : NSObject

@property (nonatomic, strong) BasicStrategy *_strategy;

-(void) makeAction;
-(void) changeStrategy:(BasicStrategy *) strategy;

@end

@implementation Player

-(void) makeAction
{
    [self._strategy actionCharacter1];
    [self._strategy actionCharacter2];
    [self._strategy actionCharacter3];
}

-(void) changeStrategy:(BasicStrategy *)strategy
{
    self._strategy = strategy;
}

@end
```

��� �����, ��� ����� ����� ������ ������ ��������� � ����������� � ����������� �� ���� ���������.
��� ��� ������������:

``` objective-c
    Player *p = [[Player alloc] init];
    AttackStrategy *a = [[AttackStrategy alloc] init];
    DefenceStrategy *d = [[DefenceStrategy alloc] init];
    
    
    [p changeStrategy:a];
    [p makeAction];
    [p changeStrategy:d];
    [p makeAction];
```

���c������ ��� ��������� ����:) � ������ ������ ���� ��������� ����� ������� ���������, � ����� ����� ��������� ����� � ������ �������. 

������������ ���:

>2013-03-04 23:57:44.797 StrategyPatterns[22420:c07] Character 1: Attack all enemies!
>
>2013-03-04 23:57:44.799 StrategyPatterns[22420:c07] Character 2: Attack all enemies!
>
>2013-03-04 23:57:44.800 StrategyPatterns[22420:c07] Character 3: Attack all enemies!
>
>2013-03-04 23:57:44.800 StrategyPatterns[22420:c07] Character 1: Attack all enemies!
>
>2013-03-04 23:57:44.801 StrategyPatterns[22420:c07] Character 2: Healing Character 1!
>
>2013-03-04 23:57:44.801 StrategyPatterns[22420:c07] Character 3: Protecting Character 2!

[��� �������.][StrategyPatterns]

## <a name="command"></a>Command

������, ������, ������ � ��� ��� �������, ������� ��� ����� ����� ������ ������� �����������. ��� ��� ��� ����� ����� ���������� � ����� �����, ����� ���� �� ������������, ��� ���-������ �� ��������� ������ � ����������� ���������.

����, ������� � ������� � ��������� ��������������� ��� ����������, ����������� ��� ���������� ������������ ��������, ������� ����� ���� ��������� �����, ��������� ������ �������.

������� ������, ���� ����� ��� � ���� ������ �������, �������� ������-����� ��������������� � ��� ������� ��������, ������ ������ ���������� �� ����� �� ����, �� �������� ��� ���� ��� ��� �������.

#### ����� ������������ �������:

��, ���������� ����� ����, � ������� �� �� ��������, ����� �� ������ ��������������� ������������ ������ � ��������� ����� �������. �������� ������ � do/undo ��������. � ���, ��������� �����, ����� ��� ��������� CommandManager, ������� ����� ����������, ��� ������ �������, � ��� ������� �������� ���������� ��������, ���� ��������� ������� undo (������, ��� ����� ���� � ������ �����).

����������, ���� ��� ���� ���������� ����� ��������:

��� ������ �������� ������� �������:

``` objective-c
@interface BaseCommand : NSObject

-(void) execute;
-(void) undo;

@end
```

��� ����� � ����� ������� �� ��� ������ � �������, � ������� ������� ���������.

������ ���������� ����� ������:

``` objective-c
@interface FirstCommand : BaseCommand
{
@private NSString *_originalString;
@private NSString *_currentString;
}

-(id) initWithArguments: (NSString *) anArgument;
-(void) printString;

@end


@implementation FirstCommand

-(id) initWithArguments:(NSString *)anArgument
{
    self = [super init];
    _originalString =  anArgument;
    _currentString = anArgument;
    
    
    return self;
}
-(void) execute
{
    _currentString = @"This is a new string";
    [self printString];
    
    NSLog(@"Execute command called");
}

-(void) undo
{
    _currentString = _originalString;
    [self printString];
    
    NSLog(@"Undo of execute command called");
}

-(void) printString
{
    NSLog(@"Current string is equal to %@", _currentString);
}

@end
```

��� �����, ���� ������ ������� ������ ����� ������ ���� �������. ������ ������ ������ ��������, ����� ����� ���� �������� ���������.

������ ���� �������:

``` objective-c
@interface SecondCommand : BaseCommand 
{
@private int _originalNumber;
@private int _currentNumber;
}

-(id) initWithArgs: (int) aNumber;
-(void) printNumber;

@end

@implementation SecondCommand

-(id) initWithArgs:(int)aNumber
{
    self = [super init];
    
    _originalNumber = aNumber;
    _currentNumber = aNumber;
    
    return self;
}

-(void) execute
{
    _currentNumber++;
    
    [self printNumber];
}

-(void) undo
{
    if (_currentNumber > _originalNumber)
        _currentNumber--;
    
    [self printNumber];
}

-(void) printNumber
{
    NSLog(@"current number is %i", _currentNumber);
}
@end
```

������ ������� ������ �� �� �����, �� � ������.

������� ������ �������� ������, ������� ����� �������� ������� � ��������� ��:

``` objective-c
@interface CommandExecutor : NSObject
{
@private NSMutableArray *_arrayOfCommands;

}

-(void) addCommand:(BaseCommand *) aCommand;
-(void) executeCommands;
-(void) undoAll;

@end

@implementation CommandExecutor

-(id) init
{
    self = [super init];
    
    _arrayOfCommands = [[NSMutableArray alloc] init];
    
    return self;
}

-(void) addCommand:(BaseCommand *) aCommand
{
    //id<CommandProtocol> item = aCommand;
    
    [_arrayOfCommands addObject:aCommand];
}

-(void) executeCommands
{
    for (BaseCommand *command in _arrayOfCommands)
    {
        [command execute];
    }
}

-(void) undoAll
{
    for (BaseCommand *command in _arrayOfCommands)
    {
        [command undo];
    }
}

@end
```

��� �����, ��� �������� ����� �������� ������� ������, � ��������� �� ���, ��� ���� �������� ��� �������� (������ ������� � � ������:) ). ����, ��� �������� ���:

``` objective-c
    CommandExecutor *commandE = [[CommandExecutor alloc] init];
    
    BaseCommand *cmdF = [[FirstCommand alloc] initWithArguments:@"This is a test string"];
    BaseCommand *cmdS = [[SecondCommand alloc] initWithArgs:3];
    
    [commandE addCommand:cmdF];
    [commandE addCommand:cmdS];
    
    [commandE executeCommands];
    [commandE undoAll];
```

� ������� �� ���:

>2013-03-06 22:40:47.392 CommandPattern[9871:c07] Current string is equal to This is a new string
>
>2013-03-06 22:40:47.393 CommandPattern[9871:c07] Execute command called
>
>2013-03-06 22:40:47.393 CommandPattern[9871:c07] current number is 4
>
>2013-03-06 22:40:47.394 CommandPattern[9871:c07] Current string is equal to This is a test string
>
>2013-03-06 22:40:47.394 CommandPattern[9871:c07] Undo of execute command called
>
>2013-03-06 22:40:47.395 CommandPattern[9871:c07] current number is 3

2. ������ ����� ���������� �������� � ��� ��� ������������� ������������� ����� Cocoa � NSInvocation:

NSInvocation � ��� ������, ������� ����� ������������, ����� �������� ����������� ������ ������ ������ ������ �������, � ��� ���� �������� � ���� ��������� ����������, � ��� �� ������ ������� ������� ���� �����.

������� � ��� CommandExecutor ������� ��� ������ � ���� ��������� ����:

``` objective-c
//private field
@private NSInvocation *_specificCommand;

//two methods:
-(void) setSpecificCommand:(NSInvocation *)aCommand
{
    _specificCommand = aCommand;
}

-(void) executeSpecificCommand
{
    [_specificCommand invoke];
}
```

��� �����, ������ ��� ������ ��������� ������ ���� NSInvocation � ����� ��� ���������, ����� ���������. ������� ������ � ����� �������� ����������� ������� �������, ������� �� ����� ��������:

``` objective-c
-(void) methodInMainController:(int) aFirstArgument andString:(NSString *)aStringArgument
{
    NSLog(@"Method called with first argument = %i and second argument = %@",
							 aFirstArgument, aStringArgument);
}
```

� ������ �������� ������ ���� NSInvocation, ������� � ����� � ���������� ����� ��������:

``` objective-c
    NSMethodSignature *signature = [self methodSignatureForSelector:
						@selector(methodInMainController:andString:)];
    NSInvocation *invocationToPass =[NSInvocation 
							invocationWithMethodSignature:signature];
    [invocationToPass setTarget:self];
    [invocationToPass setSelector:@selector(methodInMainController:andString:)];
    
    int intArgument = 3;
    NSString *stringArgument = @"This is a string argument";
    
    [invocationToPass setArgument:&intArgument atIndex:2];
    [invocationToPass setArgument:&stringArgument atIndex:3];
    
    CommandExecutor *executor = [[CommandExecutor alloc] init];
    [executor setSpecificCommand:invocationToPass];
    [executor executeSpecificCommand];
```

��� �����, � ����� ������ �� ������� ������, ������� ������ ��������� ������ ������, � ������� ������ NSInvocation. ����� ����� �� �������� � ���� ��������� � �� ����� ����������, ��� ������ ���������� � ����� 2 � index 0 � index 1 ��������������� ��� target � selector:)

�� � ������� �� ���:

>2013-03-06 23:18:26.624 CommandPattern[10479:c07] Method called with first argument = 3 and second argument = This is a string argument

[��� �������.][CommandPattern]

## <a name="flyweight"></a>Flyweight

� ���������, ��� ��������� �� � ��������� ���� ������� �� ������� �� �������� �����, � �������� ��������� ������! :D ������ ����� � �������� � ��������!

Flyweight � ������� ������� �������� ��� �������� ������������ ����������, ��� ����, ����� � ������� �������� ���� ����������� �� ������� ���������.

��� ������ ������� ����� �������������� ���� � �����������, ��� � ��� 1 ������ ������ ������ ���� � ���� ������ ����� ����� �� ���� � ��������� ���������� �������� � ����� � ��������� ����� � ��� ��� ������ ����������, ��� ������������������ ����� ������ �������. ����� ������� ���� ������ ���������� � ����� ������ ����� �������-������� � ������, �� ����.

������ �� ����� ������ �����, � ����� ������ ����������� ������.

#### ����� ������������ ���� �������?

1.	� ��� ������� ����� ��������� �������� � ����������
2.	����� �������� ��������� � ������, �� ���� ������������������ ������ ���������� ��������
3.	�� ������, ��� ��������� ��������, ������� ����� ���� ��������� � ������ ��� �� �������� ����� ������ ��������

����, ������:
����� �� ����� ����, ��� ���� ��� ���� ���������� � ������� � �������. ��� ������ �������� ������� ����� ��� ���� ������:

``` objective-c
@interface BasicUnit : NSObject

@property (nonatomic, strong) NSString *name;
@property (nonatomic) int health;
@property (nonatomic, strong) UIImage *image;

@end
```
	
��� ����� � ������� ����� ���� �������� image, ������� �������� ����� UIImage � ����� ���������� ��������� �������� ��� ������� �����. ��� �� ������� �������� ������ ��������? ��, ����������, � ���� �� � ��������� ��� �������!

``` objective-c
@interface FlyweightImageFactory : NSObject

+(UIImage *) getImage:(NSString *)imageName;

@end

@implementation FlyweightImageFactory

NSMutableDictionary *_imageDictionary;

+(UIImage *)getImage:(NSString *)imageName
{
    if (!_imageDictionary)
        _imageDictionary = [[NSMutableDictionary alloc] init];
    
    if (![_imageDictionary objectForKey:imageName])
    {
        [_imageDictionary setObject:[UIImage imageNamed:[[NSString alloc] initWithFormat:@"%@.jpeg",imageName]] forKey:imageName];
        NSLog(@"Loading image of the %@", imageName);
    }
    
    return [_imageDictionary objectForKey:imageName];
}

@end
```

��� �����, ��� flyweight ����� ������ ���� ����� �����, ������� �������� �� �����-�� � ����������. ���� �������� ��� ����� ������ ��� � ��� ������� � �� ��� �������� �� ������, ���� �� ���� � �� ������ ���������� ������ �� ���. ������ ��� ����� �������� �������� �� ������ �� �������� ���������, ��� ������� ��� ���� ����� ������� ������� ��� ���������� ��������� ����������� �� ������.

������ ��� ������ ����� � ������������ ����� ������ ��������� �������� �� �� ������, � ����� ��� �������:

``` objective-c
@implementation Dragon

-(id) init
{
    self = [super init];
    
    self.name = @"Dragon";
    self.health = 150;
    self.image = [FlyweightImageFactory getImage:@"dragon"];
    return self;
    
}

@end

@implementation Goblin

-(id) init
{
    self = [super init];
    
    self.name = @"goblin";
    self.health = 20;
    self.image = [FlyweightImageFactory getImage:@"goblin"];
    return self;
    
}

@end

�� � ������� �� ����:

    NSMutableArray *units = [[NSMutableArray alloc] init];
    for ( int i = 0 ; i < 500; i++)
    {
        [units addObject:[[Dragon alloc] init]];
    }
    for ( int i = 0 ; i < 500; i++)
    {
        [units addObject:[[Goblin alloc] init]];
    }
```

� ��� ���������, ���� �� � ������� 1 ������ ������, ��� ����������� ������ ��� ����:

>2013-03-09 11:08:45.002 FlyweightPattern[5595:c07] Loading image of the dragon
>
>2013-03-09 11:08:45.006 FlyweightPattern[5595:c07] Loading image of the goblin

[��� �������.][FlyweightPattern]
 
## <a name="proxy"></a>Proxy

��, ��� ��� �������� � ������� �������� � ��������� ������ � ��������� ����� ������:) ��� ������ ������? �� ������ �� ��� �������, ��� � �������� ��� ����� �������� ���������, ���� ��������� ����� ��� ������ ��� ����� ����� ������������� �����:

1.	�������� ��� ���� �����.
2.	�������, ����� �� ������ ���� �� �������.
3.	�������, ����� �� ������ ���������� � ��� �� ������.

�� ��� �����. ��� ��� ���������� ����� �� ������, �� ��� ���������� ������������� ������ � �������� ����� � ������ ����������� ������ � ����-����, ��� ���� ����������� ����������� ������ � ������ � �������� ���� ������.

������� ������ � ��������� �������� ������, � ���� ��� ������� ����� ���� ����������. ��� ���� ����� ��������� �������������� ������, ��� ��������� �������� ������, ���� ��� ��� �� ������.

��� ������ � �� ������ ����� ������� � ������� ������������� ����������. � ������� � ������� ������������ ����� ��������� ����� �� ������� ��������, ��� ������� ������������. ������, ��� �������, ������� �������� �� ���������� ������ � ����� ����������, �� ����������� ����� ��� ������������� ������ ����� �������������, �� ������������ ���� ������ � ������, ������� � ���� ������� ����� ��� ����� �������������, � ������� ������� ���������� �� ����� �������� ������������ ������ �������� ����.

#### ����� ������������ �������:

1.	��������, � ��� ���� ��� ������� � �������� � �����������. ����� �� �������� � ������ ����� �� ������ ���������� �������� ������, �� � ����� ������������ ���������� ��� ���������� � ������ ����� ��������. ��� ������ ����� ����������� � ������
2.	���������� ��������� ���������, � �������� ������������
3.	������� ������ ��������� ��������.

������� �������� ������. ����� � ��� ���� ������, ������� �������� �� ������ ������:

``` objective-c
@interface FileDownloader : NSObject

-(void) slowDownload;
-(void) fastDownload;

@end

@implementation FileDownloader

-(id) init
{
    self = [super init];
    NSLog(@"Downloader created");
    return self;
}


-(void) slowDownload
{
    NSLog(@"Sloooooowly downloading...");
}

-(void) fastDownload
{
    NSLog(@"Shuuuuuh, already downloaded...");
}
@end
```

��� �����, ��� ������ ����� ��������� ������ � ��������. ��� ���, ��� ��� ����� ����� ������������ � ���� �� ������� � ���������.
������� �������� ���� ������:

``` objective-c
@interface FileDownloaderProxy : NSObject
{
    @private FileDownloader *_downloader;
}


@property (nonatomic) bool isPremiumUser;

-(void) slowDownload;
-(void) fastDownload;


@end

@implementation FileDownloaderProxy


-(void) fastDownload
{
    if (!_isPremiumUser)
    {
        [self slowDownload];
        return;
    }
    
    if (!_downloader)
        _downloader = [[FileDownloader alloc] init];
    
    [self checkNetworkConnectivity];
    
    [_downloader fastDownload];
}

-(void) slowDownload
{
    if (!_downloader)
        _downloader = [[FileDownloader alloc] init];
    
    [self checkNetworkConnectivity];
    
    [_downloader slowDownload];
}

-(void) checkNetworkConnectivity
{
    NSLog(@"Checking network connectivity...");
}
@end
```

��� ����� ���������� ������������� �����:

1.	�� ����� ��� ��� ������������, � ���� ���� ������� ����� fastDownload �� ������������ �� ������� � ����� ������ ����� slowDownload.
2.	�� ����� ��������� ������ � ��������� (����� ��� � ������ ������� ����).
3.	�� ���������, ��� ��� ������� FileDownloader ������, � ���� ��� � ������� ���.

�� ���, ������������:

``` objective-c
    FileDownloaderProxy *proxy = [[FileDownloaderProxy alloc] init];
    
    [proxy setIsPremiumUser:NO];
    [proxy fastDownload];
    
    [proxy setIsPremiumUser:YES];
    [proxy fastDownload];
```

������������ ���:

>2013-03-10 13:27:50.312 ProxyPattern[10775:c07] Downloader created
>
>2013-03-10 13:27:50.313 ProxyPattern[10775:c07] Checking network connectivity�
>
>2013-03-10 13:27:50.313 ProxyPattern[10775:c07] Sloooooowly downloading�
>
>2013-03-10 13:27:50.314 ProxyPattern[10775:c07] Checking network connectivity�
>
>2013-03-10 13:27:50.314 ProxyPattern[10775:c07] Shuuuuuh, already downloaded�

[��� �������.][ProxyPattern]

## <a name="memento"></a>Memento

��, ��� �� �� ������� � ����� ����� ���� ��� Quick Save � Quick Load. �� ����� ����� Ctrl + Z. ��� � ��� ��� ������ ��������� ������! ���������, ����� ���������� ����� ������� ��� ���������� � ����������. ����� ��������� ����� �������� ���� ���������� ��������� �� ������ ������, ����� � ��� �� ������ ������ ���������.

����, ��� �� �� ������� �����? Memento � ������� ������� ���������, �� ������� ������������, ������������� � ��������� ���������� ��������� �������, ����� ����� ������������ ��� ���������.

���������, ��� �������, ����� ����������� ��� � �������� �������, ��� � � ���� �����. ����� ������ ������������� � ����� ���� ������������ � ���������� ������ ���������� � �� ����� ���������� ���������� �� ������ ��������� ��� ������ � �����, ��� ���������, ��� ��� ��� ��� ������ � ���� ����� ����� CoreData, ����� ������������ ��� ���������.

����� ������������ �������:

1.	��� ���������� ��������� ��������� ������� ��� ������ (snapshot) �� ������������ ������
2.	�� ������ ������ ��������� ��������� ��������� �������.

� ����� �������� ������������ ��� �������� �������: Caretaker (������, ������� �������� ���������� ���������� ��������� �������), originator (���������� ��� ������) � ������� �� ��� Memento (������, ������� ��������� ��������� originator).

������� ��������� ������:

``` objective-c
@interface OriginatorState : NSObject

@property (nonatomic) int intValue;
@property (nonatomic) NSString *stringValue;

@end

@implementation OriginatorState
@end
```

��������, � ��� ���� ���������, � ������� ����� ���� ��� ��������� � ������������� � �������.

``` objective-c
@interface Originator : NSObject
{
@private OriginatorState *_localState;
}

-(void) changeValues;
-(OriginatorState *) getState;
-(void) setState:(OriginatorState *)oldState;
@end

@implementation Originator

-(id) init
{
    self = [super init];
    
    _localState = [[OriginatorState alloc] init];
    _localState.intValue = 100;
    _localState.stringValue = @"Hello World!";
    
    return self;
}

-(void) changeValues
{
    _localState.intValue++;
    _localState.stringValue = [NSString stringWithFormat:@"%@ %@", _localState.stringValue, @"!"];
    
    NSLog(@"Current state int = %i, string = %@", _localState.intValue, _localState.stringValue);
}

-(OriginatorState *) getState
{
    return _localState;
}

-(void) setState:(OriginatorState *)oldState
{
    _localState = oldState;
    
     NSLog(@"Load completed. Current state: int = %i, string = %@", _localState.intValue, _localState.stringValue);
}
@end
```

��� �����, �� ����� �������� ��������� ������� ���������, � ��� �� �������� ��������� � ��������� ���������.

����� � ��� ���� Memento � ������, ������� ����� ���������� ���������� ������ �������:

``` objective-c
@interface Memento : NSObject
{
@private OriginatorState *_localState;
}

-(id) initWithState:(OriginatorState *)state;
-(OriginatorState*) getState;
@end

@implementation Memento

-(id) initWithState:(OriginatorState *)state
{
    self = [super init];
    
    _localState = [[OriginatorState alloc] init];
    [_localState setIntValue:state.intValue];
    [_localState setStringValue:state.stringValue];
    
    return self;
}

-(OriginatorState *) getState
{
    return _localState;
}
@end
```

�� ���� ��� ������ Memento � ����� ������� ���������, �, ������� ��, �������� ��������� :)
�� � ������, �������� ��� ��� � ������ �����, �������� Caretaker:

``` objective-c
@interface Caretaker : NSObject
{
@private Originator *_originator;
@private Memento *_memento;
}

-(void) changeValue;
-(void) saveState;
-(void) loadState;
@end

@implementation Caretaker

-(void) changeValue
{
    if (!_originator)
        _originator = [[Originator alloc] init];
    
    [_originator changeValues];
}

-(void) saveState
{
    _memento = [[Memento alloc] initWithState:[_originator getState]];
    NSLog(@"Saved state. State int = %i and string = %@",[[_memento getState] intValue ], [[_memento getState] stringValue ]);
}

-(void) loadState
{
    [_originator setState:[_memento getState]];
}

@end
```

��� �����, Caretaker ����� ������� � ���� ����������� ��������� (��� �������, ��� ��� ����� ������, �� ����� ����� ���� � ���� ���������, � ��� �����), � ��� �� ��������� ���:)

������� ���������:

``` objective-c
    Caretaker *crtaker = [[Caretaker alloc] init];
    
    [crtaker changeValue];
    [crtaker saveState];
    [crtaker changeValue];
    [crtaker changeValue];
    [crtaker changeValue];
    [crtaker loadState];
```

��� ��� ������ ������ ��������:

>2013-03-11 23:23:30.711 MementoPattern[14985:c07] Current state int = 101, string = Hello World! !
>
>2013-03-11 23:23:30.712 MementoPattern[14985:c07] Saved state. State int = 101 and string = Hello World! !
>
>2013-03-11 23:23:30.712 MementoPattern[14985:c07] Current state int = 102, string = Hello World! ! !
>
>2013-03-11 23:23:30.713 MementoPattern[14985:c07] Current state int = 103, string = Hello World! ! ! !
>
>2013-03-11 23:23:30.713 MementoPattern[14985:c07] Current state int = 104, string = Hello World! ! ! ! !.
>
>2013-03-11 23:23:30.713 MementoPattern[14985:c07] Load completed. Current state: int = 101, string = Hello World! !

[��� �������.][MementoPattern]

[PrototypePattern]:https://github.com/dimko1/ios_patterns/tree/master/PrototypePattern
[FactoryMethodPattern]:https://github.com/dimko1/ios_patterns/tree/master/FactoryMethodPattern
[AbstractFabric]:https://github.com/dimko1/ios_patterns/tree/master/AbstractFabric
[BuilderPattern]:https://github.com/dimko1/ios_patterns/tree/master/BuilderPattern
[SingletonPattern]:https://github.com/dimko1/ios_patterns/tree/master/SingletonPattern
[AdapterPattern]:https://github.com/dimko1/ios_patterns/tree/master/AdapterPattern
[BridgePattern]:https://github.com/dimko1/ios_patterns/tree/master/BridgePattern
[FacadePattern]:https://github.com/dimko1/ios_patterns/tree/master/FacadePattern
[MediatorPattern]:https://github.com/dimko1/ios_patterns/tree/master/MediatorPattern
[ObserverPattern]:https://github.com/dimko1/ios_patterns/tree/master/ObserverPattern
[CompositePattern]:https://github.com/dimko1/ios_patterns/tree/master/CompositePattern
[IteratorPattern]:https://github.com/dimko1/ios_patterns/tree/master/IteratorPattern
[VisitorPattern]:https://github.com/dimko1/ios_patterns/tree/master/VisitorPattern
[DecoratorPattern]:https://github.com/dimko1/ios_patterns/tree/master/DecoratorPattern
[ChainOfResponsibility]:https://github.com/dimko1/ios_patterns/tree/master/ChainOfResponsibility
[TemplateMethod]:https://github.com/dimko1/ios_patterns/tree/master/TemplateMethod
[StrategyPatterns]:https://github.com/dimko1/ios_patterns/tree/master/StrategyPatterns
[CommandPattern]:https://github.com/dimko1/ios_patterns/tree/master/CommandPattern
[FlyweightPattern]:https://github.com/dimko1/ios_patterns/tree/master/FlyweightPattern
[ProxyPattern]:https://github.com/dimko1/ios_patterns/tree/master/ProxyPattern
[MementoPattern]:https://github.com/dimko1/ios_patterns/tree/master/MementoPattern
