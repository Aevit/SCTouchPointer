# SCTouchPointer
show the touch pointer

## Preview
![image](https://raw.githubusercontent.com/Aevit/SCTouchPointer/master/demo.gif)  

--- 

## Public properties and methods

```
/**
 show pointer view when touch
 
 @param pointRadius the touch pointer view radius, if your pass '0', it will be the default data 15
 
 @param pointColor the touch pointer view color, if you pass 'nil', it will be the deafult data: [UIColor colorWithRed:253/255.0 green:129/255.0 blue:129/255.0 alpha:1];
 */
void sc_installTouchPointer(CGFloat pointRadius, UIColor *pointColor);


/**
 NOT pointer view when touch
 */
void sc_uninstallTouchPointer();
```

---

## Usage

copy the folder `SCTouchPointer` to your project, and then code like below:  

* show the pointer  

```
sc_installTouchPointer(15, [UIColor blueColor]);
``` 

* NOT show the pointer

```
sc_uninstallTouchPointer();
```

---

## License

This code is distributed under the terms and conditions of the [MIT license](https://raw.githubusercontent.com/Aevit/SCTouchPointer/master/LICENSE). 