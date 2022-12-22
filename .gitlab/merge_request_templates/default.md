### [💠 Jira]() [🔘 Demo]()

[ดูรายชื่อคนที่เกี่ยวข้องในแต่ละโปรเจค](https://wiki.wndv.co/pages/viewpage.action?pageId=5669845)

#### Warning อย่าลืมใส่ prefix ที่ commit msg ก่อน merge !!

[วิธีเติม prefix](https://wiki.wndv.co/display/FRONTEND/Wongnai+Web+Deployment)

##### Why I did
<!--- ทำไมถึงต้องทำ MR นี้ -->
-

##### What I did
<!--- ทำอะไรไปบ้าง มี feature อะไรเพิ่มเข้ามา แก้แล้วกระทบอะไรไปบ้าง -->
-

##### How I test
<!--- เขียน Unit test อะไรไปบ้าง -->
-

##### Checklists

###### Required

- [ ] merge เข้า branch dev เพื่อ test
- [ ] Unit test ที่เขียนเป็นไปตาม test spec ใน task
- [ ] มี Unit test ครอบคลุมทุกไฟล์ใหม่ที่เพิ่มเข้ามา และต้องมี coverage > 80
- [ ] Code เป็นไปตาม [React Code Conventions](https://wiki.wndv.co/display/FRONTEND/React+Code+Conventions)
- [ ] Code เป็นไปตาม [React Review code Guideline](https://wiki.wndv.co/display/FRONTEND/React+Review+code+Guideline)
- [ ] รีวิวโค้ดตัวเองแล้วอย่างถี่ถ้วน

##### Ignite Requirement

- [ ] แยกไฟล์ styled-component ออกมาเป็น `styled.ts`
- [ ] หากมี variant ให้แยกคุณสมบัติต่าง ๆ ออกมาแล้วสร้างเป็นโฟลเดอร์ `variants / [variant name].ts`
- [ ] หากมี size ให้แยกค่าต่าง ๆ ของไซส์นั้นออกมาเป็นสร้างเป็นโฟลเดอร์ `sizes / [size].ts`
- [ ] ทุก Component's props type ต้อง extends `ComponentPropsWithRef` ด้วยเสมอ
- [ ] รับ props ที่ส่งเข้ามาลงไปใน children component เสมอ

###### Minor

- [ ] Test Coverage ไฟล์ใหม่และไฟล์ที่แก้ > 80
- [ ] ถ้ามี change > 50 ให้จัด commit เพื่อให้รีวิวโค้ดได้ง่าย

##### Review
<!--- อยากให้คนรีวิวช่วยดูจุดไหนเพิ่มเติม แบ่ง commit review ที่นี่ -->

- 