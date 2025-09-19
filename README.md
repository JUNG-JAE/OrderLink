# OrderLink
Order food together to easily meet the minimum order amount and save on delivery fees.

## 1. Acknowledgement
+ This project was conducted as part of the course **Software Engineering** at Gachon university.
+ **Team Leader**: Jungjae Lee
+ **Team Member**: MinJe Seok

---

## 2. Introduction
The COVID-19 pandemic has led to a boom in the food delivery industry, with a continuous increase in food delivery orders. Paradoxically, this surge has created negative consequences for both consumers and small business owners, primarily due to the minimum order amount required for delivery. To solve this problem, we propose the development of "Delivery Share," an SNS-style application.

---

## 3. Problem Definition (Technical Specification)
1. To implement an SNS application that connects users based on location to place group food orders, thereby helping them meet minimum order requirements.
2. During signup, users must provide required profile data, including a nickname, address, and gender.
3. User profiles, which are viewable by other users, will display information such as nickname, gender, and user ratings.
4. Users gain access to the application's services by logging in.
5. The user's current location will default to the address provided during signup. Users can also manually change their current location as needed.
6. The main screen will display posts from other users in the vicinity, based on the current user's location.
7. Users can create new posts on the board based on their current address.
8. When creating a post, users must specify the food menu, the maximum duration for the post to remain active, and the maximum number of people for the group order. Optional additional details can also be provided.
9. The board will show a preview of each post, displaying essential information: the food menu, the post's expiration time, and the maximum group size.
10. A post will be deactivated if its time expires or the maximum number of participants is reached. It will be reactivated if a participant leaves, making a spot available.
11. Other users can select a post to view its required order information and additional details, as well as the profile of the post's creator.
12. Users who apply to join a post can communicate with each other through a dedicated in-app messenger.
13. Through the messenger, users can chat and finalize the details for their group delivery order.
14. After the order is completed, users can rate each other. These ratings will be reflected on their respective profiles.

---

## 4. Gantt Chart
<img width="1635" height="536" alt="WorkSheet_ver1" src="https://github.com/user-attachments/assets/f36c9d82-ab63-4be9-9c07-8da2ab946515" />

---

## 5. Requirement
+ **Android Compiler Version**: API Android 11.0 R, AVD: R(Pixel2)
+ **Firebase SDK**: 11.8.0

---

## 6. Preview
<div align="center">
  <table style="border-collapse: collapse; border: none;">
    <tr>
      <td align="center" style="border: none;"><b>Board Detail</b></td>
      <td align="center" style="border: none;"><b>Board List</b></td>
    </tr>
    <tr>
      <td align="center" style="border: none;">
        <img src="https://github.com/user-attachments/assets/470dbdde-702c-4aa2-a0e7-9017ec5da717" width="300" height="490">
      </td>
      <td align="center" style="border: none;">
        <img src="https://github.com/user-attachments/assets/5cd8a4bf-8220-475f-80bb-3964cf09dee4" width="300" height="490">
      </td>
    </tr>
    <tr>
      <td align="center" style="border: none;"><b>Set GPS</b></td>
      <td align="center" style="border: none;"><b>Profile</b></td>
    </tr>
    <tr>
      <td align="center" style="border: none;">
        <img src="https://github.com/user-attachments/assets/40d43072-b359-4d0a-8064-503efc4e1037" width="300" height="490">
      </td>
      <td align="center" style="border: none;">
        <img src="https://github.com/user-attachments/assets/cff1d4a2-0f66-4f38-9fbe-269b12997a13" width="300" height="490">
      </td>
    </tr>
  </table>
</div>
