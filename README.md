# PersianRender


# Installation

## Composer

You can install this package using [composer](https://getcomposer.org). Add this package to your `composer.json`:  

```
"require": {
	"eskandari/persianrender": "dev-master"
}
```

# Manual

```

 \PersianRender\PersianRender::render('کتابخانه ی رندر GD image در php');

```

Gd image example
```

  $text  = \PersianRender\PersianRender::render('فارسی'); //Reversed text for GD
 imagettftext ( $image ,  $size ,  $angle , $x , $y ,$color , $fontfile , $text );
  
```
<p align="center"><a href="#">نمونه فارسی نویسی با فونت دانا<img src="./example-1.png" alt="Image"></a></p>
<p align="center"><a href="#">نمونه فارسی نویسی با فونت کلمه<img src="./example-2.png" alt="Image"></a></p>

