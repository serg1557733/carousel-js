JavaScript carousel code
![image](https://user-images.githubusercontent.com/72445490/139540609-d64c40c8-1c20-4771-a28b-0bb9e8d0b3fd.png)

using 

html 

<div class="offer__slider">
        <div class="offer__slider-counter">
            <div class="offer__slider-prev">
                <img src="img/slider/left.svg" alt="prev">
            </div>
            <span id="current">03</span>
            <span id="total">04</span>
            <div class="offer__slider-next">
                <img src="img/slider/right.svg" alt="next">
            </div>
        </div>
        <div class="offer__slider-wrapper">
            <div class="offer__slider-inner">
                <div class="offer__slide">
                    <img src="img/slider/pepper.jpg" alt="pepper">
                </div>
                <div class="offer__slide">
                    <img src="img/slider/food-12.jpg" alt="food">
                </div>
                <div class="offer__slide">
                    <img src="img/slider/olive-oil.jpg" alt="oil">
                </div>
                <div class="offer__slide">
                    <img src="img/slider/paprika.jpg" alt="paprika">
                </div>
            </div>
        </div>
 </div>

    and pure JS function 

slider(slideClass, sliderMainWrapperClass, sliderNextClass, sliderPrevClass,sliderWrapperClass, sliderInnerWrapperClass )

as arguments use classes from index.html 
slideClass,  
sliderMainWrapperClass, 
sliderNextClass, 
sliderPrevClass,
sliderWrapperClass, 
sliderInnerWrapperClass 

slider('.offer__slide', '.offer__slider', '.offer__slider-prev', '.offer__slider-next', '.offer__slider-wrapper', '.offer__slider-inner');
