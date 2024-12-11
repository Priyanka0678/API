## **Table of Contents**

## 

**[What Is an API?	2](#what-is-an-api?)**

[**API Main Components	2**](#api-main-components)

[**How Does The API Work?	3**](#how-does-the-api-work?)

[**Types of APIs	4**](#types-of-apis)

[**API Usage Example	4**](#api-usage-example)

[**Advantages Of API	5**](#advantages-of-api)

[**Conclusion**	**5**](#conclusion)

## 

## 

## 

## 

### **What Is an API?** {#what-is-an-api?}

![][image1]

API ka full form hai **Application Programming Interface**. Yeh ek tarika hai jisse do applications aapas mein communicate karte hain bina kisi direct user ke intervAPI ko ek waiter ki tarah samjha ja sakta hai jo kitchen aur customer ke beech ka connection hai. Jaise waiter order leta hai aur kitchen se food lata hai, waise hi API bhi ek request ko process karke response laata hai.

API waiter ki tarah kaam karta hai jo **customer** (app) aur **kitchen** (backend server) ke beech ka bridge hai. Waiter aapka order kitchen tak le jaata hai aur khana (data) wapas lekar aata hai. Is process mein, aapko kitchen mein jaake khana banane ki zarurat nahi hai — bas waiter ko bata do, aur kaam ho jaayega\! Isi tarah, APIs software applications ke beech information exchange karne mein madad karti hain bina kisi direct user interference ke.

### **API Main Components** {#api-main-components}

1. **Request**: Jab hum kuchh specific information chahte hain, toh hum ek request bhejte hain. Jaise, agar app ko weather ka data chahiye, toh woh ek request bhejta hai API ko.  
2. **Endpoint**: API mein alag-alag functions ya services hoti hain jinko hum access kar sakte hain. Yeh endpoints hote hain, jaise `/search`  
3. **Response**: API request ko process karke response bhejta hai. Yeh response mostly JSON ya XML format mein hota hai jo structured hota hai jise hum easily read kar sakte hai.

### 

### **How Does The API Work?** {#how-does-the-api-work?}

**1.Request Bhejna:**  
Aap (client) waiter ko bula kar kehte hain: "Mujhe ek pizza chahiye".  
Waise hi, client (app ya browser) API ko ek request bhejta hai. Example: "Mujhe Mumbai ke pizza restaurants ki list chahiye."

**2.Data Processing:**  
Waiter (API) kitchen (backend) mein jaata hai aur order (data) process karwata hai.  
Backend server ya database se data retrieve hota hai aur process kiya jaata hai.

**3.Response Wapas Bhejna:**  
Jaise waiter aapko pizza lekar aata hai, waise hi API backend se response lekar client ko wapas bhejti hai.

    


### **Types of APIs** {#types-of-apis}

**REST API (Representational State Transfer):**

* Yeh API architecture ka ek popular format hai.  
* Data ko access karne ke liye HTTP methods like GET, POST, PUT, DELETE ka use kiya jata hai.  
* REST APIs usually lightweight hoti hain aur response JSON format mein hota hai.

**SOAP API (Simple Object Access Protocol):**

* Yeh APIs zyada secure aur strict hoti hain.  
* SOAP APIs usually XML format mein data ko send aur receive karti hain.

### **API Usage Example** {#api-usage-example}

**Restaurant Search API:**

1. **Request:**  /search?query=pizza\&location=mumbai  
2. **Process:** API server pe data retrieve hota hai. ex.API backend mein jaake, location aur food item ke basis pe relevant restaurants ki list retrieve karta hai jo pizza serve karte hain.  
3. **Response:** JSON format mein response milta hai.  
     
   

### 

### 

### **Advantages Of API** {#advantages-of-api}

* **Automation**: APIs se tasks ko automate kar sakte hain jaise data fetch karna ya updates.  
* **Data Access**: APIs se data ko access karna aasaan hota hai.  
* **Scalability**: APIs ko aap easily scale kar sakte hain agar zyada data ya services integrate karni ho.

### **Conclusion** {#conclusion}

Toh, API ek bridge ki tarah hai jo applications ko ek doosre se connect karta hai. Aap API ki madad se data aur functionalities ko access aur integrate kar sakte ho bina directly kisi aur application ke internal code ko touch kiye.

[image1]: <data:image/png;base64,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>