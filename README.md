import React from "react";
import Carousel from "react-multi-carousel";
import "react-multi-carousel/lib/styles.css";

const ServicesCarousel = () => {
  return (
    <Carousel
      additionalTransfrom={0}
      arrows
      autoPlaySpeed={3000}
      centerMode={false}
      className=""
      containerClass="container-with-dots"
      dotListClass=""
      draggable
      focusOnSelect={false}
      infinite
      itemClass=""
      keyBoardControl
      minimumTouchDrag={80}
      pauseOnHover
      renderArrowsWhenDisabled={false}
      renderButtonGroupOutside={false}
      renderDotsOutside={false}
      responsive={{
        desktop: {
          breakpoint: {
            max: 3000,
            min: 1024,
          },
          items: 3,
          partialVisibilityGutter: 40,
        },
        mobile: {
          breakpoint: {
            max: 464,
            min: 0,
          },
          items: 1,
          partialVisibilityGutter: 30,
        },
        tablet: {
          breakpoint: {
            max: 1024,
            min: 464,
          },
          items: 2,
          partialVisibilityGutter: 30,
        },
      }}
      rewind={false}
      rewindWithAnimation={false}
      rtl={false}
      shouldResetAutoplay
      showDots={false}
      sliderClass=""
      slidesToSlide={1}
      swipeable
    >
      {/* Replace WithStyles with your actual content */}
      <div>
        <h2>Slide 1</h2>
        <img src="https://example.com/image1.jpg" alt="Slide 1" />
        <p>Description of slide 1</p>
      </div>
      <div>
        <h2>Slide 2</h2>
        <img src="https://example.com/image2.jpg" alt="Slide 2" />
        <p>Description of slide 2</p>
      </div>
      <div>
        <h2>Slide 2</h2>
        <img src="https://example.com/image2.jpg" alt="Slide 2" />
        <p>Description of slide 2</p>
      </div>
      <div>
        <h2>Slide 2</h2>
        <img src="https://example.com/image2.jpg" alt="Slide 2" />
        <p>Description of slide 2</p>
      </div>
      <div>
        <h2>Slide 2</h2>
        <img src="https://example.com/image2.jpg" alt="Slide 2" />
        <p>Description of slide 2</p>
      </div>
      <div>
        <h2>Slide 2</h2>
        <img src="https://example.com/image2.jpg" alt="Slide 2" />
        <p>Description of slide 2</p>
      </div>
      <div>
        <h2>Slide 2</h2>
        <img src="https://example.com/image2.jpg" alt="Slide 2" />
        <p>Description of slide 2</p>
      </div>
      <div>
        <h2>Slide 2</h2>
        <img src="https://example.com/image2.jpg" alt="Slide 2" />
        <p>Description of slide 2</p>
      </div>
      {/* Add more slides as needed */}
    </Carousel>
  );
};

export default ServicesCarousel;
