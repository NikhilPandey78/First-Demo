import React from "react";
import "..CardsAndContent.css"; // Assuming you have a CSS file for styling
import Techimage1 from "../Assets/Tech-image-1.webp";
import Techimage2 from "../Assets/Tech-image-2.webp";
import Techimage3 from "../Assets/Tech-image-3.webp";
import Techimage4 from "../Assets/Tech-image-4.webp";

function CardsAndContent() {
  return (
    <>
      <div className="container mt-5 mb-5 text-center">
        <h2>Courses</h2>
        <p>
          We offer programs in Engineering, Polytechnic ,Management, and P
          harmacy, designed to give you the skills you need for your future
          career. Our experienced teachers make sure you get a great education
          and are ready for the workforce when you graduate. Discover your
          options and start your journey with us at RITM.
        </p>
      </div>
      <div>
        <img src={Techimage1} alt="" />
        <div>
          <img src={Techimage2} alt="" />
        </div>
        <div>
          <img src={Techimage3} alt="" />
        </div>
        <div>
          <img src={Techimage4} alt="" />
        </div>
      </div>
    </>
  );
}
export default CardsAndContent;
