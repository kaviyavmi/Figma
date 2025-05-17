# Ex09 Event Registration Web Application
## Date: 17-05-2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
HOME PAGE

<div style="width: 598.45px; height: 967.19px; position: relative; background: #F5F5F5; overflow: hidden">
  <img style="width: 566.18px; height: 831.30px; left: -3px; top: 137.25px; position: absolute" src="https://placehold.co/566x831" />
  <div style="width: 211.86px; left: 166.14px; top: 305px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 40px; font-family: Inter; font-weight: 700; word-wrap: break-word">MAY 16<br/></div>
  <img style="width: 565.20px; height: 158.63px; left: -2.21px; top: -11.58px; position: absolute" src="https://placehold.co/565x159" />
  <div style="left: 130px; top: 248px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 32px; font-family: Inter; font-weight: 800; word-wrap: break-word">SEC EVENT DAY 2</div>
  <div style="width: 444.86px; height: 92.33px; left: 57.14px; top: 790px; position: absolute; background: #7B34FF; border-radius: 50px"></div>
  <div style="left: 138.06px; top: 806px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 32px; font-family: Inter; font-weight: 800; word-wrap: break-word">REGISTER  NOW......</div>
  <img style="width: 223.66px; height: 223.66px; left: 187.34px; top: 427px; position: absolute; border-radius: 60px" src="https://placehold.co/224x224" />
  <div style="left: 182.07px; top: 704px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 40px; font-family: Inter; font-weight: 700; word-wrap: break-word">DRESTIN’25</div>
</div>


 import React from "react";
import styled from "styled-components";

const StyledImage3625 = styled.img`
  width: 566.18px;
  height: 831.30px;
  left: -3px;
  top: 137.25px;
  position: absolute;
`;

const StyledMay16span = styled.span`
  color: white;
  font-size: 40px;
  font-family: Inter;
  font-weight: 700;
  word-wrap: break-word;
`;

const StyledWhatsAppImage20250511at140620de2d80c41 = styled.img`
  width: 565.20px;
  height: 158.63px;
  left: -2.21px;
  top: -11.58px;
  position: absolute;
`;

const StyledSeceventday2span = styled.span`
  color: white;
  font-size: 32px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
`;

const StyledRectangle1430106570 = styled.div`
  width: 444.86px;
  height: 92.33px;
  left: 57.14px;
  top: 790px;
  position: absolute;
  background: #7B34FF;
  border-radius: 50px;
`;

const StyledRegisternowspan = styled.span`
  color: white;
  font-size: 32px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
`;

const StyledWhatsAppImage20250511at174940dacd3d641 = styled.img`
  width: 223.66px;
  height: 223.66px;
  left: 187.34px;
  top: 427px;
  position: absolute;
  border-radius: 60px;
`;

const StyledDrestin25span = styled.span`
  color: white;
  font-size: 40px;
  font-family: Inter;
  font-weight: 700;
  word-wrap: break-word;
`;

const StyledHOMEPAGE = styled.div`
  width: 598.45px;
  height: 967.19px;
  position: relative;
  background: #F5F5F5;
  overflow: hidden;
`;

export const HomePage = () => {
  return (
    <StyledHOMEPAGE>
      <StyledImage3625  src="https://placehold.co/566x831"/>
      <StyledMAY16>MAY 16<br/></StyledMAY16>
      <StyledWhatsAppImage20250511at140620de2d80c41  src="https://placehold.co/565x159"/>
      <StyledSECEVENTDAY2>SEC EVENT DAY 2</StyledSECEVENTDAY2>
      <StyledRectangle1430106570 />
      <StyledREGISTERNOW>REGISTER  NOW......</StyledREGISTERNOW>
      <StyledWhatsAppImage20250511at174940dacd3d641  src="https://placehold.co/224x224"/>
      <StyledDRESTIN25>DRESTIN’25</StyledDRESTIN25>
    </StyledHOMEPAGE>
  );
};

EVENT DETAILS


<div style="width: 560px; height: 946px; position: relative; background: white; overflow: hidden">
  <img style="width: 720px; height: 1280px; left: -50px; top: -303px; position: absolute" src="https://placehold.co/720x1280" />
  <div style="width: 449px; height: 94px; left: 45px; top: 212px; position: absolute; background: rgba(0, 0, 0, 0.50)"></div>
  <div style="left: 131px; top: 241px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 40px; font-family: Inter; font-weight: 700; word-wrap: break-word">EVENT  LIST</div>
  <div style="width: 265.05px; height: 186px; left: 45.45px; top: 269px; position: absolute"></div>
  <div style="width: 465px; left: 19px; top: 306px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: #F8FFEF; font-size: 32px; font-family: Inter; font-weight: 700; word-wrap: break-word">SOLO SINGING </div>
  <div style="width: 505px; height: 380px; left: 16px; top: 439px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 32px; font-family: Inter; font-weight: 700; word-wrap: break-word">2.TENTUKOTTA<br/><br/>3.FULL STACK DEVELOPMENT WORKSHOP<br/><br/>4.SOLO DANCING<br/><br/>5.INDUSTRIAL VISIT AT TAMBARAM<br/><br/>6.WEBINAR<br/></div>
  <div style="width: 409px; height: 104px; left: 75px; top: 816px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 32px; font-family: Inter; font-weight: 700; word-wrap: break-word">7.GAMING DEVELOPMENT</div>
  <img style="width: 438.28px; height: 292px; left: 55px; top: -51px; position: absolute" src="https://placehold.co/438x292" />
</div>

import React from "react";
import styled from "styled-components";

const StyledImage3627 = styled.img`
  width: 720px;
  height: 1280px;
  left: -50px;
  top: -303px;
  position: absolute;
`;

const StyledRectangle1430106562 = styled.div`
  width: 449px;
  height: 94px;
  left: 45px;
  top: 212px;
  position: absolute;
  background: rgba(0, 0, 0, 0.50);
`;

const StyledEventlistspan = styled.span`
  color: white;
  font-size: 40px;
  font-family: Inter;
  font-weight: 700;
  word-wrap: break-word;
`;

const StyledStar9 = styled.div`
  width: 265.05px;
  height: 186px;
  left: 45.45px;
  top: 269px;
  position: absolute;
`;

const StyledSolosingingspan = styled.span`
  color: #F8FFEF;
  font-size: 32px;
  font-family: Inter;
  font-weight: 700;
  word-wrap: break-word;
`;

const Styled2tentukotta3fullstackdevelopmentworkshop4solodancing5industrialvisitattambaram6webinarspan = styled.span`
  color: white;
  font-size: 32px;
  font-family: Inter;
  font-weight: 700;
  word-wrap: break-word;
`;

const Styled7gamingdevelopmentspan = styled.span`
  color: white;
  font-size: 32px;
  font-family: Inter;
  font-weight: 700;
  word-wrap: break-word;
`;

const StyledWhatsAppImage20250511at162200b43c13511 = styled.img`
  width: 438.28px;
  height: 292px;
  left: 55px;
  top: -51px;
  position: absolute;
`;

const StyledEVENTDETAILS = styled.div`
  width: 560px;
  height: 946px;
  position: relative;
  background: white;
  overflow: hidden;
`;

export const EventDetails = () => {
  return (
    <StyledEVENTDETAILS>
      <StyledImage3627  src="https://placehold.co/720x1280"/>
      <StyledRectangle1430106562 />
      <StyledEVENTLIST>EVENT  LIST</StyledEVENTLIST>
      <StyledStar9 />
      <StyledSOLOSINGING>SOLO SINGING </StyledSOLOSINGING>
      <Styled2TENTUKOTTA3FULLSTACKDEVELOPMENTWORKSHOP4SOLODANCING5INDUSTRIALVISITATTAMBARAM6WEBINAR>2.TENTUKOTTA<br/><br/>3.FULL STACK DEVELOPMENT WORKSHOP<br/><br/>4.SOLO DANCING<br/><br/>5.INDUSTRIAL VISIT AT TAMBARAM<br/><br/>6.WEBINAR<br/></Styled2TENTUKOTTA3FULLSTACKDEVELOPMENTWORKSHOP4SOLODANCING5INDUSTRIALVISITATTAMBARAM6WEBINAR>
      <Styled7GAMINGDEVELOPMENT>7.GAMING DEVELOPMENT</Styled7GAMINGDEVELOPMENT>
      <StyledWhatsAppImage20250511at162200b43c13511  src="https://placehold.co/438x292"/>
    </StyledEVENTDETAILS>
  );
};

REGISTER PAGE

<div style="width: 573px; height: 956px; position: relative; background: white; overflow: hidden">
  <img style="width: 779.46px; height: 1170px; left: -77px; top: -218px; position: absolute" src="https://placehold.co/779x1170" />
  <div style="left: 76px; top: 761px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 32px; font-family: Inter; font-weight: 800; word-wrap: break-word">EVENT NAME</div>
  <div style="left: 76px; top: 430px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 32px; font-family: Inter; font-weight: 800; word-wrap: break-word">REG NUMBER</div>
  <div style="left: 76px; top: 344px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 32px; font-family: Inter; font-weight: 800; word-wrap: break-word">LAST NAME</div>
  <div style="width: 5px; height: 0px; left: 103px; top: 133px; position: absolute; transform: rotate(180deg); transform-origin: top left; outline: 1px white solid; outline-offset: -0.50px"></div>
  <div style="width: 100px; height: 100px; left: 132px; top: 275px; position: absolute"></div>
  <div style="left: 76px; top: 244px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 32px; font-family: Inter; font-weight: 800; word-wrap: break-word">FULL NAME<br/></div>
  <div style="left: 76px; top: 513px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 32px; font-family: Inter; font-weight: 800; word-wrap: break-word">COLLEGE NAME</div>
  <div style="left: 76px; top: 601px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 32px; font-family: Inter; font-weight: 800; word-wrap: break-word">MOBILE NUMBER</div>
  <div style="left: 76px; top: 683px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 32px; font-family: Inter; font-weight: 800; word-wrap: break-word">EMAIL ID<br/></div>
  <div style="width: 353px; height: 66px; left: 27px; top: 235px; position: absolute; background: rgba(217, 217, 217, 0.30); border-radius: 40px"></div>
  <div style="width: 353px; height: 61px; left: 34px; top: 336px; position: absolute; background: rgba(217, 217, 217, 0.43); border-radius: 40px"></div>
  <div style="width: 353px; height: 61px; left: 27px; top: 419px; position: absolute; background: rgba(217, 217, 217, 0.41); border-radius: 40px"></div>
  <div style="width: 353px; height: 58px; left: 34px; top: 504px; position: absolute; background: rgba(217, 217, 217, 0.34); border-radius: 40px"></div>
  <div style="width: 353px; height: 60px; left: 27px; top: 588px; position: absolute; background: rgba(217, 217, 217, 0.34); border-radius: 40px"></div>
  <div style="width: 353px; height: 57px; left: 34px; top: 677px; position: absolute; background: rgba(217, 217, 217, 0.44); border-radius: 40px"></div>
  <div style="width: 353px; height: 63px; left: 34px; top: 760px; position: absolute; background: rgba(217, 217, 217, 0.36); border-radius: 40px"></div>
  <div style="width: 445px; height: 121px; left: 76px; top: 70px; position: absolute; background: rgba(180.04, 143.69, 255, 0.70)"></div>
  <div style="width: 421px; height: 70px; left: 98px; top: 101px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: #FF0000; font-size: 32px; font-family: Inter; font-weight: 800; word-wrap: break-word">REGISTRATION FORM!!!!</div>
  <div style="width: 445px; height: 71px; left: 43px; top: 847px; position: absolute; background: #7F0EFF; border-radius: 20px"></div>
  <div style="left: 172px; top: 866px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: black; font-size: 32px; font-family: Inter; font-weight: 800; word-wrap: break-word">REGISTER!!!</div>
</div>

import React from "react";
import styled from "styled-components";

const StyledImage3626 = styled.img`
  width: 779.46px;
  height: 1170px;
  left: -77px;
  top: -218px;
  position: absolute;
`;

const StyledEventnamespan = styled.span`
  color: white;
  font-size: 32px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
`;

const StyledRegnumberspan = styled.span`
  color: white;
  font-size: 32px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
`;

const StyledLastnamespan = styled.span`
  color: white;
  font-size: 32px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
`;

const StyledLine78 = styled.div`
  width: 5px;
  height: 0px;
  left: 103px;
  top: 133px;
  position: absolute;
  transform: rotate(180deg);
  transform-origin: top left;
  outline: 1px white solid;
  outline-offset: -0.50px;
`;

const StyledFrame2147238120 = styled.div`
  width: 100px;
  height: 100px;
  left: 132px;
  top: 275px;
  position: absolute;
`;

const StyledFullnamespan = styled.span`
  color: white;
  font-size: 32px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
`;

const StyledCollegenamespan = styled.span`
  color: white;
  font-size: 32px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
`;

const StyledMobilenumberspan = styled.span`
  color: white;
  font-size: 32px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
`;

const StyledEmailidspan = styled.span`
  color: white;
  font-size: 32px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
`;

const StyledRectangle1430106563 = styled.div`
  width: 353px;
  height: 66px;
  left: 27px;
  top: 235px;
  position: absolute;
  background: rgba(217, 217, 217, 0.30);
  border-radius: 40px;
`;

const StyledRectangle1430106564 = styled.div`
  width: 353px;
  height: 61px;
  left: 34px;
  top: 336px;
  position: absolute;
  background: rgba(217, 217, 217, 0.43);
  border-radius: 40px;
`;

const StyledRectangle1430106565 = styled.div`
  width: 353px;
  height: 61px;
  left: 27px;
  top: 419px;
  position: absolute;
  background: rgba(217, 217, 217, 0.41);
  border-radius: 40px;
`;

const StyledRectangle1430106566 = styled.div`
  width: 353px;
  height: 58px;
  left: 34px;
  top: 504px;
  position: absolute;
  background: rgba(217, 217, 217, 0.34);
  border-radius: 40px;
`;

const StyledRectangle1430106567 = styled.div`
  width: 353px;
  height: 60px;
  left: 27px;
  top: 588px;
  position: absolute;
  background: rgba(217, 217, 217, 0.34);
  border-radius: 40px;
`;

const StyledRectangle1430106568 = styled.div`
  width: 353px;
  height: 57px;
  left: 34px;
  top: 677px;
  position: absolute;
  background: rgba(217, 217, 217, 0.44);
  border-radius: 40px;
`;

const StyledRectangle1430106569 = styled.div`
  width: 353px;
  height: 63px;
  left: 34px;
  top: 760px;
  position: absolute;
  background: rgba(217, 217, 217, 0.36);
  border-radius: 40px;
`;

const StyledRectangle1430106571 = styled.div`
  width: 445px;
  height: 121px;
  left: 76px;
  top: 70px;
  position: absolute;
  background: rgba(180.04, 143.69, 255, 0.70);
`;

const StyledRegistrationformspan = styled.span`
  color: #FF0000;
  font-size: 32px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
`;

const StyledRectangle1430106572 = styled.div`
  width: 445px;
  height: 71px;
  left: 43px;
  top: 847px;
  position: absolute;
  background: #7F0EFF;
  border-radius: 20px;
`;

const StyledRegisterspan = styled.span`
  color: black;
  font-size: 32px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
`;

const StyledREGISTERPAGE = styled.div`
  width: 573px;
  height: 956px;
  position: relative;
  background: white;
  overflow: hidden;
`;

export const RegisterPage = () => {
  return (
    <StyledREGISTERPAGE>
      <StyledImage3626  src="https://placehold.co/779x1170"/>
      <StyledEVENTNAME>EVENT NAME</StyledEVENTNAME>
      <StyledREGNUMBER>REG NUMBER</StyledREGNUMBER>
      <StyledLASTNAME>LAST NAME</StyledLASTNAME>
      <div></div>
      <StyledFrame2147238120 />
      <StyledFULLNAME>FULL NAME<br/></StyledFULLNAME>
      <StyledCOLLEGENAME>COLLEGE NAME</StyledCOLLEGENAME>
      <StyledMOBILENUMBER>MOBILE NUMBER</StyledMOBILENUMBER>
      <StyledEMAILID>EMAIL ID<br/></StyledEMAILID>
      <StyledRectangle1430106563 />
      <StyledRectangle1430106564 />
      <StyledRectangle1430106565 />
      <StyledRectangle1430106566 />
      <StyledRectangle1430106567 />
      <StyledRectangle1430106568 />
      <StyledRectangle1430106569 />
      <StyledRectangle1430106571 />
      <StyledREGISTRATIONFORM>REGISTRATION FORM!!!!</StyledREGISTRATIONFORM>
      <StyledRectangle1430106572 />
      <StyledREGISTER>REGISTER!!!</StyledREGISTER>
    </StyledREGISTERPAGE>
  );
};

LAST PAGE

<div style="width: 606px; height: 956px; position: relative; background: #764BFF; overflow: hidden">
  <img style="width: 2500px; height: 3380px; left: -964px; top: -1609px; position: absolute" src="https://placehold.co/2500x3380" />
  <img style="width: 606.70px; height: 317px; left: 0px; top: 104px; position: absolute" src="https://placehold.co/607x317" />
  <div style="left: 52px; top: 520px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: black; font-size: 32px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">FURTHER DETAIILS</div>
  <div style="left: 49px; top: 596px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: black; font-size: 32px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">CONTACT HERE</div>
  <div style="left: 35px; top: 672px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: black; font-size: 32px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">+91 76798 37983</div>
  <img style="width: 157.24px; height: 179.60px; left: 386.38px; top: 520px; position: absolute" src="https://placehold.co/157x180" />
  <div style="left: 7px; top: 799px; position: absolute; text-align: center; justify-content: center; display: flex; flex-direction: column; color: #800EFF; font-size: 40px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">CO ORDINATOR: NITHYASREE</div>
</div>

import React from "react";
import styled from "styled-components";

const StyledImage3628 = styled.img`
  width: 2500px;
  height: 3380px;
  left: -964px;
  top: -1609px;
  position: absolute;
`;

const StyledImage3629 = styled.img`
  width: 606.70px;
  height: 317px;
  left: 0px;
  top: 104px;
  position: absolute;
`;

const StyledFurtherdetaiilsspan = styled.span`
  color: black;
  font-size: 32px;
  font-family: Inter;
  font-style: italic;
  font-weight: 800;
  word-wrap: break-word;
`;

const StyledContactherespan = styled.span`
  color: black;
  font-size: 32px;
  font-family: Inter;
  font-style: italic;
  font-weight: 800;
  word-wrap: break-word;
`;

const Styled917679837983span = styled.span`
  color: black;
  font-size: 32px;
  font-family: Inter;
  font-style: italic;
  font-weight: 800;
  word-wrap: break-word;
`;

const StyledImage3630 = styled.img`
  width: 157.24px;
  height: 179.60px;
  left: 386.38px;
  top: 520px;
  position: absolute;
`;

const StyledCoordinatornithyasreespan = styled.span`
  color: #800EFF;
  font-size: 40px;
  font-family: Inter;
  font-style: italic;
  font-weight: 900;
  word-wrap: break-word;
`;

const StyledLASTPAGE = styled.div`
  width: 606px;
  height: 956px;
  position: relative;
  background: #764BFF;
  overflow: hidden;
`;

export const LastPage = () => {
  return (
    <StyledLASTPAGE>
      <StyledImage3628  src="https://placehold.co/2500x3380"/>
      <StyledImage3629  src="https://placehold.co/607x317"/>
      <StyledFURTHERDETAIILS>FURTHER DETAIILS</StyledFURTHERDETAIILS>
      <StyledCONTACTHERE>CONTACT HERE</StyledCONTACTHERE>
      <Styled917679837983>+91 76798 37983</Styled917679837983>
      <StyledImage3630  src="https://placehold.co/157x180"/>
      <StyledCOORDINATORNITHYASREE>CO ORDINATOR: NITHYASREE</StyledCOORDINATORNITHYASREE>
    </StyledLASTPAGE>
  );
};
```

## OUTPUT:

![output figma](https://github.com/user-attachments/assets/34eb76f1-929c-444c-8358-ce5adcce7dc7)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
