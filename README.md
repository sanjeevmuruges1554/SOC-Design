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
 1000  Unit Distance= 1 Micron \
Die within Unit Distance = 660685 − 0 = 660685 \
Die height in unit Distance = 671405 − 0 = 671405 \
Distance in Microns=Value in Unit Distance 1000\
Die width in Microns = 660685 1000 = 660.685 MIcrons
Die Height in Microns = 671405 1000 = 671.405 Microns\
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
### 5. Post-Layout ngspice simulations
![Screenshot from 2024-10-18 22-35-18](https://github.com/user-attachments/assets/689ac044-7aa6-4798-80df-39e1f70b8022)
![Screenshot from 2024-10-18 22-35-30](https://github.com/user-attachments/assets/8c70544a-82bb-4a5c-a580-ef1cd0c18ac0)
![Screenshot from 2024-10-18 22-36-34](https://github.com/user-attachments/assets/466a1989-2dca-482a-a79f-b20a2aebc05e)
![Screenshot from 2024-10-18 22-37-12](https://github.com/user-attachments/assets/451b5d45-5fdc-4c00-8e76-6e4ce37a74e2)
![Screenshot from 2024-10-18 22-37-18](https://github.com/user-attachments/assets/83e15849-9eac-4e29-b985-9ea80abec226)
![Screenshot from 2024-10-18 22-38-24](https://github.com/user-attachments/assets/56b56150-4472-4859-896c-ef0d05afe5b8)
![Screenshot from 2024-10-18 22-38-39](https://github.com/user-attachments/assets/09d9bee4-bfcb-4fd3-8833-65cd0bd2aab9)
### 6. Find problem in DRC section of magic file
![Screenshot from 2024-10-18 22-40-11](https://github.com/user-attachments/assets/080f9802-86a1-4b0d-969e-59620d257ccc)
![Screenshot from 2024-10-18 22-43-36](https://github.com/user-attachments/assets/4b1a1e94-e1be-4062-9a30-60feeb394be2)
## Section 4-Pre-layout timing analysis and imposrtanceof good clock tree
![Screenshot from 2024-10-18 22-54-14](https://github.com/user-attachments/assets/c87cf397-75a8-4e42-81fc-d5786f78b3ca)
![Screenshot from 2024-10-18 22-57-06](https://github.com/user-attachments/assets/2eea1763-ca38-4531-a5b5-2415a59c6ae7)
### 1.Fix up small DRC errors
![Screenshot from 2024-10-18 22-57-45](https://github.com/user-attachments/assets/4ddeb6ec-847b-4ae7-ba42-370459f6e3bb)
![Screenshot from 2024-10-18 23-02-29](https://github.com/user-attachments/assets/79820154-90ad-4cdb-ba04-86a37bf853ec)
### 2.Save the finalized layout and open it
![Screenshot from 2024-10-18 23-10-20](https://github.com/user-attachments/assets/0595d617-03c1-4abf-b226-44ee3e4e588b)
### 3.Edit config.tcl
![Screenshot from 2024-10-18 23-51-02](https://github.com/user-attachments/assets/65ff6382-ce46-469f-9b18-60be4f80306f)
![Screenshot from 2024-10-18 23-51-58](https://github.com/user-attachments/assets/48544fb5-b3d5-4fe2-a751-ac0c0ebd2a91)
![Screenshot from 2024-10-18 23-53-15](https://github.com/user-attachments/assets/cd9086e6-c4a2-40f0-964c-4b69a79f2aaf)
###  5. Remove and reduce newly introduced violations
![Screenshot from 2024-10-18 23-54-34](https://github.com/user-attachments/assets/cf6a54f2-10da-4846-95df-67149e6f63d6)
![Screenshot from 2024-10-18 23-54-39](https://github.com/user-attachments/assets/ee94075d-c779-42ca-80ea-01fe1bcc33dd)
![Screenshot from 2024-10-19 00-15-49](https://github.com/user-attachments/assets/2737f774-2e8b-4fa4-a268-5132f8a1fe5a)
![Screenshot from 2024-10-19 00-24-36](https://github.com/user-attachments/assets/a555031a-befb-42fb-bce2-904cbb6e8da2)
![Screenshot from 2024-10-19 00-26-06](https://github.com/user-attachments/assets/22762caf-92d3-41e7-83e8-adfad7b6b84c)
![Screenshot from 2024-10-19 00-28-00](https://github.com/user-attachments/assets/bc011323-335a-4665-aaf7-d2d179ce6b60)
![Screenshot from 2024-10-19 00-28-04](https://github.com/user-attachments/assets/0cada9cc-3194-418c-bb95-42aa48c176cf)
![Screenshot from 2024-10-19 00-28-21](https://github.com/user-attachments/assets/80baa484-1e83-45b9-aa2f-12f84f6cff69)
![Screenshot from 2024-10-19 00-28-51](https://github.com/user-attachments/assets/9c0f15e6-a498-4fb1-8cdb-8a14d7ef9560)
### 6.Once Synthesis is over run floorplan
![Screenshot from 2024-10-19 00-29-01](https://github.com/user-attachments/assets/bad8f728-0c8f-4127-a2dc-151f114ee151)
![Screenshot from 2024-10-19 00-29-07](https://github.com/user-attachments/assets/35a03231-f487-4845-9ca6-7778a30eac5d)
![Screenshot from 2024-10-19 00-29-16](https://github.com/user-attachments/assets/018576bc-e912-4c97-99ce-920938c7d619)
![Screenshot from 2024-10-19 00-29-26](https://github.com/user-attachments/assets/ae2af296-575a-4d0b-9fc7-4d8aa5ec3d45)
![Screenshot from 2024-10-19 00-29-39](https://github.com/user-attachments/assets/82d0d1fa-1d95-428d-b734-c6a998a5a5a6)
![Screenshot from 2024-10-19 00-30-29](https://github.com/user-attachments/assets/01edeee2-83e6-4397-924c-e16255e6b371)
![Screenshot from 2024-10-19 00-32-00](https://github.com/user-attachments/assets/9db5aec2-cd44-46f7-9f69-b07a0fbef28c)
![Screenshot from 2024-10-19 00-32-40](https://github.com/user-attachments/assets/4b44295f-b9b3-4523-af83-2a4d5fb6e9bb)
![Screenshot from 2024-10-19 00-34-23](https://github.com/user-attachments/assets/1120014f-7a99-4532-9413-04f887bbaa52)
![Screenshot from 2024-10-19 00-34-36](https://github.com/user-attachments/assets/b40b33ca-bb00-43c7-9027-46a630f908b9)
![Screenshot from 2024-10-19 00-39-55](https://github.com/user-attachments/assets/6b20b12c-ea2e-4ad5-9ec8-e5d4a79b9987)
![Screenshot from 2024-10-19 01-17-56](https://github.com/user-attachments/assets/cd2ffdca-a11c-4684-b000-8813375692b9)
![Screenshot from 2024-10-19 01-18-44](https://github.com/user-attachments/assets/736b8393-b966-4522-8508-621c61a74e0a)
![Screenshot from 2024-10-19 01-19-05](https://github.com/user-attachments/assets/f2fd5b0f-0a64-4591-93e2-644e4b73a454)
![Screenshot from 2024-10-19 01-19-08](https://github.com/user-attachments/assets/63e639fa-0d5f-4c12-aa1b-282ac582aaf7)
![Screenshot from 2024-10-19 01-26-25](https://github.com/user-attachments/assets/a9a6317f-bb14-4a42-9888-254c72e4d348)
![Screenshot from 2024-10-19 01-27-46](https://github.com/user-attachments/assets/0fc80801-f3e9-4266-b853-0540463e40c0)
![Screenshot from 2024-10-19 01-28-02](https://github.com/user-attachments/assets/19d60827-8edc-4c3f-a2db-8ea82332500a)
![Screenshot from 2024-10-19 01-28-31](https://github.com/user-attachments/assets/3c6e0d40-8dd1-4048-a30b-28b4898118c2)
![Screenshot from 2024-10-19 01-28-41](https://github.com/user-attachments/assets/70354b11-24c3-45d3-9f6b-ef48684a2e95)
![Screenshot from 2024-10-19 01-28-46](https://github.com/user-attachments/assets/aca6384a-533a-4103-b13a-94f7de43f07b)
![Screenshot from 2024-10-19 01-28-52](https://github.com/user-attachments/assets/9b7fc232-80bb-4125-a467-c61a69f1f859)
### 7.Make timing ECO fixes to remove all violations
![Screenshot from 2024-10-19 01-29-20](https://github.com/user-attachments/assets/5f954f7d-927c-4725-8675-f51b32626920)
![Screenshot from 2024-10-19 01-31-23](https://github.com/user-attachments/assets/f199aced-1ec8-455c-912c-1636ab14c9ba)
![Screenshot from 2024-10-19 01-31-50](https://github.com/user-attachments/assets/802753a0-77bf-4619-806d-6d7f7fd54e78)
![Screenshot from 2024-10-19 01-32-53](https://github.com/user-attachments/assets/cfa00a8a-b686-460c-b6c8-cc7c17e058d8)
![Screenshot from 2024-10-19 01-34-29](https://github.com/user-attachments/assets/7c71ec67-334c-4ae0-9cc5-8276cfba8b25)
![Screenshot from 2024-10-19 01-34-33](https://github.com/user-attachments/assets/b0642c66-9b68-47b8-a8ff-818a120173e3)
![Screenshot from 2024-10-19 01-34-51](https://github.com/user-attachments/assets/58780248-e2bd-4e67-b8f3-fb72a9bcf677)
![Screenshot from 2024-10-19 01-35-03](https://github.com/user-attachments/assets/3ab425d7-ac29-4602-b797-11b7eab79a49)
![Screenshot from 2024-10-19 01-35-28](https://github.com/user-attachments/assets/06721d08-f9e4-49a0-8d15-cf6b7f173358)
![Screenshot from 2024-10-19 01-38-46](https://github.com/user-attachments/assets/89786992-8e75-473f-9279-fe968ace826c)
![Screenshot from 2024-10-19 01-38-57](https://github.com/user-attachments/assets/e1bae44a-50df-4311-8d05-3caf7d67c114)
![Screenshot from 2024-10-19 01-40-29](https://github.com/user-attachments/assets/ec4b967b-4b10-467e-abee-a16f59e3c33a)
![Screenshot from 2024-10-19 01-41-11](https://github.com/user-attachments/assets/03edbf0c-0c6e-4e26-a069-6610ef88b9b3)
![Screenshot from 2024-10-19 01-42-42](https://github.com/user-attachments/assets/23bf4c83-32a9-479e-bdbf-c8cb2105a3b4)
![Screenshot from 2024-10-19 01-44-07](https://github.com/user-attachments/assets/3098304c-71d2-405f-901f-12909dd54040)
![Screenshot from 2024-10-19 01-46-00](https://github.com/user-attachments/assets/24e05d0b-a0a1-4cf1-8244-582f58778e81)
![Screenshot from 2024-10-19 01-49-05](https://github.com/user-attachments/assets/17608737-593d-4b74-9111-7aa1114aef83)
![Screenshot from 2024-10-19 01-53-20](https://github.com/user-attachments/assets/3f8cc48f-a391-459f-ab0d-181a6a70ccc5)
![Screenshot from 2024-10-19 01-54-55](https://github.com/user-attachments/assets/11d50430-ff43-46e4-aaf4-884d4313a26c)
![Screenshot from 2024-10-19 01-56-28](https://github.com/user-attachments/assets/27c158eb-830a-4629-a8da-2abc7df1c2ce)
![Screenshot from 2024-10-19 01-58-16](https://github.com/user-attachments/assets/c293ad34-15e2-4bcf-b8e8-2ae05d2fcc84)
![Screenshot from 2024-10-19 01-58-40](https://github.com/user-attachments/assets/2968985b-090f-41c6-a95d-d89273e66bc9)
![Screenshot from 2024-10-19 01-59-07](https://github.com/user-attachments/assets/75413e0f-02d4-43c5-bb14-9168abe3f8e8)
![Screenshot from 2024-10-19 02-00-29](https://github.com/user-attachments/assets/95ae15fb-cc70-4bec-811c-f5e950da3e7d)
![Screenshot from 2024-10-19 02-03-15](https://github.com/user-attachments/assets/852ee1b0-7f23-439a-8401-1d90e5154213)
### 9.Post-CTS
![Screenshot from 2024-10-19 03-03-01](https://github.com/user-attachments/assets/0327550b-9c7e-4c20-9135-01ab269f94f5)
![Screenshot from 2024-10-19 03-03-06](https://github.com/user-attachments/assets/daae318e-4c7f-4143-9d9d-5bfc921d4f4d)
![Screenshot from 2024-10-19 03-10-53](https://github.com/user-attachments/assets/9008e21b-7a99-4989-b087-303bc8287bbc)
![Screenshot from 2024-10-19 03-11-00](https://github.com/user-attachments/assets/75e62c06-057a-4805-b924-621b543a113c)
![Screenshot from 2024-10-19 03-11-04](https://github.com/user-attachments/assets/9888808e-7d36-4835-9927-7f96931f9dfb)
![Screenshot from 2024-10-19 03-11-07](https://github.com/user-attachments/assets/6346e790-da6e-4241-917d-9b490f8a69a3)
![Screenshot from 2024-10-19 03-14-42](https://github.com/user-attachments/assets/afea1508-4787-4a5e-9595-5d06b347f41b)
![Screenshot from 2024-10-19 03-15-25](https://github.com/user-attachments/assets/07829baa-3e0f-41fc-8d36-7537d69f1a9d)
### 10.Post-CTS after removing a cell
![Screenshot from 2024-10-19 03-24-18](https://github.com/user-attachments/assets/52810ae7-05b4-450c-aa97-4626677af6cc)
![Screenshot from 2024-10-19 03-25-06](https://github.com/user-attachments/assets/fefe5d84-f50a-40d0-80dd-99a2cd843eda)
![Screenshot from 2024-10-19 03-25-32](https://github.com/user-attachments/assets/67a7c6e2-6dba-460e-809a-17aa748ee714)
## Section 5
### 1.Perform deneration of PDN and explore the layout
![Screenshot from 2024-10-19 03-27-38](https://github.com/user-attachments/assets/f0dd7e66-9749-4e47-a382-6f26b0f0a4da)
![Screenshot from 2024-10-19 03-27-51](https://github.com/user-attachments/assets/cf3ae6f9-e639-4dd8-a7c3-fe76b3e158f7)
![Screenshot from 2024-10-19 03-37-20](https://github.com/user-attachments/assets/59824a97-f0a7-4d26-b4db-aca370f206fe)
![Screenshot from 2024-10-19 03-38-10](https://github.com/user-attachments/assets/22f9e2ad-f066-4539-b8a4-b942b4711f1e)
![Screenshot from 2024-10-19 03-38-28](https://github.com/user-attachments/assets/76441e43-675f-4dc0-b128-eb1bf6b6d4ab)
### 2. Detailed Routing with TritonRoute and explore
![Screenshot from 2024-10-19 03-39-46](https://github.com/user-attachments/assets/90bdf003-f4af-4b08-997e-34b090a358b0)
![Screenshot from 2024-10-19 04-08-10](https://github.com/user-attachments/assets/eeee3fea-dc72-42fd-81c5-d0d2790022bc)
![Screenshot from 2024-10-19 04-08-30](https://github.com/user-attachments/assets/72f17d29-baa3-4b49-ba22-44083c6e2225)
![Screenshot from 2024-10-19 04-12-20](https://github.com/user-attachments/assets/a93732c7-f4bf-4f12-9f4c-3ef9217e211e)
![Screenshot from 2024-10-19 04-12-33](https://github.com/user-attachments/assets/6f2ca787-d5c8-4a01-ac0f-82dd5a1bde23)
![Screenshot from 2024-10-19 04-13-03](https://github.com/user-attachments/assets/47c9304b-ec89-4dfa-92a7-9c34c0572ab1)
![Screenshot from 2024-10-19 04-13-37](https://github.com/user-attachments/assets/3eaae65a-2f03-4731-91e6-57a8afa1f898)
![Screenshot from 2024-10-19 04-14-41](https://github.com/user-attachments/assets/68491760-3785-46f5-b43a-64975a5b92df)
### 3.Post route parasitic extractiion using SPEF extractor
![Screenshot from 2024-10-19 04-31-02](https://github.com/user-attachments/assets/61eb846a-1488-40d1-84bb-829766d2c04b)
### 4.Post-Route openSTA STA
![Screenshot from 2024-10-19 04-31-09](https://github.com/user-attachments/assets/8d0c0141-2071-459c-bd15-ce2535d92ce8)
![Screenshot from 2024-10-19 04-31-13](https://github.com/user-attachments/assets/54a9eef1-fa20-4c45-ab8a-803fc8f9519b)
![Screenshot from 2024-10-19 04-31-15](https://github.com/user-attachments/assets/8c8cbca3-ee32-4235-964a-7411804e82b5)
![Screenshot from 2024-10-19 04-31-17](https://github.com/user-attachments/assets/46a5037e-6dd9-42ea-8974-2a423453a386)
![Screenshot from 2024-10-19 04-31-23](https://github.com/user-attachments/assets/9f0e8f40-b6c9-4ede-861e-55f36778d67d)

