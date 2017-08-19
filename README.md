# PersianRender


# Installation

## Using Composer

You can install this package using [composer](https://getcomposer.org). Add this package to your `composer.json`:  

```
"require": {
	"eskandari/persianrender": "dev-master"
}
```

# manual

```

 \PersianRender\PersianRender::render('کتابخانه ی رندر GD image در php');

```

using in the Gd image
```

  $text  = \PersianRender\PersianRender::render('فارسی',true); //Reversed text for GD
  
  imagettftext ( $image ,  $size ,  $angle , $x , $y ,$color , $fontfile , $text );
  
```
