# SOC-Design
## Section 1 
### 1. Run 'picorv32a'synthesis:
![Screenshot from 2024-10-18 19-11-25](https://github.com/user-attachments/assets/a78e6729-6a09-489f-82bb-0698fc0858ed)
![Screenshot from 2024-10-18 19-11-48](https://github.com/user-attachments/assets/485313ef-53fd-448e-bf83-dcfe3ba4918d)
![Screenshot from 2024-10-18 19-12-15](https://github.com/user-attachments/assets/4caba8aa-4e9a-4938-91c2-3178fcc6ac06)
![Screenshot from 2024-10-18 19-13-03](https://github.com/user-attachments/assets/f378bc95-42ff-4cbb-a215-2dfa69445dc5)
### 2. Calculate the Flop Ratio
![Screenshot from 2024-10-18 19-29-12](https://github.com/user-attachments/assets/b5e06a49-b54b-4a71-902f-f1114dafe3f3)
 Flop Ratio= 1213/14876= 0.108429685
 Percentage of DFF's= 0.108429685*100= 10.84296854
 ## Section 2: Floorplan and Library Cells
 ### 1. Run Floorplan
![Screenshot from 2024-10-18 19-39-35](https://github.com/user-attachments/assets/6d0791bb-80dc-44c9-9cb7-a3cf8d460209)
![Screenshot from 2024-10-18 19-39-47](https://github.com/user-attachments/assets/816692ce-6fe7-4a71-916d-81cecc3208a7)
### 2. Calculate Die Area
![Screenshot from 2024-10-18 19-43-01](https://github.com/user-attachments/assets/db313a2f-0502-4be5-88b1-bb07add8ee78)
 1000  Unit Distance= 1 Micron \\
Die within Unit Distance = 660685 − 0 = 660685 \\
Die height in unit Distance = 671405 − 0 = 671405 \\
Distance in Microns=Value in Unit Distance 1000\\
Die width in Microns = 660685 1000 = 660.685 MIcrons\\
Die Height in Microns = 671405 1000 = 671.405 Microns\\
Area of Die in Microns = 660.685 ∗ 671.405 = 443587.212425Square Microns

### 3. Load Generated floorplan in Magic
![Screenshot from 2024-10-18 19-58-05](https://github.com/user-attachments/assets/92e9c495-79b9-4443-a9b4-b5445e8b56ac)
![Screenshot from 2024-10-18 19-59-43](https://github.com/user-attachments/assets/cbec5ffc-133c-418b-b1f0-1e3dfd7db9c1)
![Screenshot from 2024-10-18 20-00-29](https://github.com/user-attachments/assets/21065f14-978a-4099-86c9-eb2cb341e440)
![Screenshot from 2024-10-18 20-00-54](https://github.com/user-attachments/assets/d8166ff6-3a16-4e2a-abf7-69314f5c2278)
![Screenshot from 2024-10-18 20-01-29](https://github.com/user-attachments/assets/91f019d5-a1d1-4547-bb54-83526da98270)
![Screenshot from 2024-10-18 20-01-46](https://github.com/user-attachments/assets/2ca0a35b-e2fc-449f-8dc6-8f5132b6b109)
### 4.Run congestion aware placement
![Screenshot from 2024-10-18 20-02-09](https://github.com/user-attachments/assets/e2c529ec-8ec8-49d9-9f8d-f514ad53cf8e)
![Screenshot from 2024-10-18 20-02-40](https://github.com/user-attachments/assets/1c176fe1-8c17-41fd-906e-30e960fec894)
### 5. Load denerated placement def in Magic and explore the placement
![Screenshot from 2024-10-18 20-04-37](https://github.com/user-attachments/assets/a4e172ba-381c-42f0-8e35-f053440a9df7)
![Screenshot from 2024-10-18 20-05-06](https://github.com/user-attachments/assets/2fb49415-3d31-4b50-b436-92bfc21b46a5)
## Section 3
### 1.Clone custom inverter cell 
![Screenshot from 2024-10-18 20-11-36](https://github.com/user-attachments/assets/50561fa5-cc4f-4af9-9f85-103007d355f4)
### 2.Load the layout in Magic and explore
![Screenshot from 2024-10-18 20-11-46](https://github.com/user-attachments/assets/969c7e20-c5ef-4dc1-8664-0468525f707c)
![Screenshot from 2024-10-18 20-31-54](https://github.com/user-attachments/assets/8435dda7-5d4f-4201-9f9c-3bc2482124d5)
![Screenshot from 2024-10-18 20-32-25](https://github.com/user-attachments/assets/2ad84ea2-f2db-4627-9757-9f957f0e6b66)
![Screenshot from 2024-10-18 20-33-43](https://github.com/user-attachments/assets/70863da2-cf25-4092-900d-e23c0c5a3bd7)
![Screenshot from 2024-10-18 20-34-22](https://github.com/user-attachments/assets/7d31b17f-b5fa-405d-8173-8b3b63b0680d)
### 3. SPICE extraction of inverter in Magic
![Screenshot from 2024-10-18 20-43-18](https://github.com/user-attachments/assets/2282dd2d-6c1f-4d73-9a7e-86874d6c71bf)
![Screenshot from 2024-10-18 20-44-08](https://github.com/user-attachments/assets/a53dcfa1-738f-428c-b9dd-9a9a99170109)
### 4. Editing the SPICE model file for analysis through simulation
![Screenshot from 2024-10-18 20-46-46](https://github.com/user-attachments/assets/5f54acc5-fd6b-463d-b614-8dc1591d5f30)
![Screenshot from 2024-10-18 22-34-49](https://github.com/user-attachments/assets/16da83dd-d6c7-4d3b-babd-05b0acadec9a)
![Screenshot from 2024-10-18 22-35-18](https://github.com/user-attachments/assets/689ac044-7aa6-4798-80df-39e1f70b8022)
### 5. Post-Layout ngspice simulations
![Screenshot from 2024-10-18 22-35-30](https://github.com/user-attachments/assets/8c70544a-82bb-4a5c-a580-ef1cd0c18ac0)
![Screenshot from 2024-10-18 22-36-34](https://github.com/user-attachments/assets/466a1989-2dca-482a-a79f-b20a2aebc05e)
![Screenshot from 2024-10-18 22-37-12](https://github.com/user-attachments/assets/451b5d45-5fdc-4c00-8e76-6e4ce37a74e2)
![Screenshot from 2024-10-18 22-37-18](https://github.com/user-attachments/assets/83e15849-9eac-4e29-b985-9ea80abec226)
![Screenshot from 2024-10-18 22-38-24](https://github.com/user-attachments/assets/56b56150-4472-4859-896c-ef0d05afe5b8)
![Screenshot from 2024-10-18 22-38-39](https://github.com/user-attachments/assets/09d9bee4-bfcb-4fd3-8833-65cd0bd2aab9)
![Screenshot from 2024-10-18 22-40-11](https://github.com/user-attachments/assets/080f9802-86a1-4b0d-969e-59620d257ccc)
### 6. Find problem in DRC section of magic file
![Screenshot from 2024-10-18 22-43-36](https://github.com/user-attachments/assets/4b1a1e94-e1be-4062-9a30-60feeb394be2)
![Screenshot from 2024-10-18 22-54-14](https://github.com/user-attachments/assets/c87cf397-75a8-4e42-81fc-d5786f78b3ca)
![Screenshot from 2024-10-18 22-57-06](https://github.com/user-attachments/assets/2eea1763-ca38-4531-a5b5-2415a59c6ae7)
![Screenshot from 2024-10-18 22-57-45](https://github.com/user-attachments/assets/4ddeb6ec-847b-4ae7-ba42-370459f6e3bb)
4
![Screenshot from 2024-10-18 23-02-29](https://github.com/user-attachments/assets/79820154-90ad-4cdb-ba04-86a37bf853ec)
