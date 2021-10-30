**JavaScript carousel code**

html classes for function and pure JS function 

slider(slideClass, sliderMainWrapperClass, sliderNextClass, sliderPrevClass,sliderWrapperClass, sliderInnerWrapperClass )
><div class="offer__slider">
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



> as arguments use classes from index.html 
slideClass -  '.offer__slide'
sliderMainWrapperClass  -  '.offer__slider'
sliderNextClass  -  '.offer__slider-prev'
sliderPrevClass  - '.offer__slider-next'
sliderWrapperClass  - '.offer__slider-wrapper'
sliderInnerWrapperClass -  '.offer__slider-inner'

slider('.offer__slide', '.offer__slider', '.offer__slider-prev', '.offer__slider-next', '.offer__slider-wrapper', '.offer__slider-inner');

![image](https://user-images.githubusercontent.com/72445490/139540688-9bff1020-b498-4685-a7ee-e5bf4d9102e3.png)
