---
layout: default
title: Technical Vault
---

<!-- 
====================================================================================
📝 INVISIBLE REUSABLE SYMBOLS CHEAT SHEET (HOW TO USE MARKDOWN SYMBOLS)
This section is a comment. It is completely hidden on your compiled public website!
====================================================================================

# (Hashtag + Space) 
-> MAIN WORKBOOK TITLE: Use this exactly ONCE at the absolute top of your document files.

## (Two Hashtags + Space) 
-> MAJOR CHAPTER DIRECTORIES: Use this to mark distinct major subjects (like Embedded C vs Drivers).

### (Three Hashtags + Space) 
-> QUESTION MODULE HEADERS: Type this before any question. Your CSS overrides it instantly, 
   painting it GeeksforGeeks Green and appending a 🟢 dot icon ahead of your line automatically.

--- (Three Dashes in a single row) 
-> PAGE DIVIDER SEGMENT: Draws a full-width line across screens to slice up separate questions.

* (Asterisk + Space) or - (Dash + Space)
-> DYNAMIC LINK DIRECTORY BULLETS: Used to map your floating menu items. Indenting these links 
   using spacing tracks sub-hierarchies ("Embedded C" -> "Questions Answers:" -> "Clickable Link").

> (Greater Than Sign + Space) 
-> INTERVIEW STUDY CALLOUT BOX: Converts standard paragraphs instantly into green tip containers.

```c ... ``` (Three Backticks on separate rows encapsulation)
-> SYNTAX HIGH-LIGHTED CODE BLOCKS: Embeds C firmware scripts inside clean engineering boxes.

![Alternate Text Description Here](./images/your_file.png)
-> AUTOMATED IMAGE CENTERING LOADER: Place this link format to render driver design charts. 
   Your CSS intercepts this call to center graphics and trace border frames with zero html.

<span class="my-sym">ANY_EMOJI_OR_CHARACTER_HERE</span>
-> USER-DEFINED VARIABLE SYMBOL: Wrap any custom symbol or icon inside this span tag. 
   The CSS will format and align it instantly to match your theme!

====================================================================================
-->

# Embedded Software Interview Questions & Answers

---
---
## 🛠️ Category: Generic

### Q1. What's Volatile?

* **Ans:** The `volatile` keyword tells the compiler optimizer that a variable's value can change at any moment outside the control of the running source code block.
* This explicitly forces the CPU architecture to re-fetch the variable contents directly from actual physical memory space arrays every single time it is accessed, bypassing unsafe compiler cache variables.
* <span class="my-sym">⭐</span> Important validation marker.
* <span class="my-sym">⚡</span> Register specific notice.

```c
volatile uint32_t *status_reg = (uint32_t *)0x40003000;
while (*status_reg == 0); 
```

> **Interview Tip:** Always apply `volatile` attributes when tracing memory-mapped input/output address bounds, managing tracking flags modified deep inside an ISR context, or sharing parameters between different execution blocks inside a multi-threaded RTOS environment.

---
### Q1. What's a Device Driver?

* **Ans:** A device driver is a highly specialized kernel-space software framework module that operates as a direct translator between the core operating system kernel architecture and specific external physical hardware assets.
* It wraps complex pin register mechanics into universal software models so that user applications can use unified file handling routines like `open()`, `read()`, and `write()`.

#### Driver-to-Hardware Architecture Diagram:
![Device Driver Architecture Flowchart](./images/driver_flow.png)

> **Interview Tip:** Writing custom device driver code blocks demands rigorous memory verification methodologies. Because driver processes operate inside un-sandboxed kernel-space boundaries, a single pointer leak or memory race fault will execute a full-scale operating system crash (Kernel Panic).
---
### 🚀 Next

## 🛠️ Category: Introduction & Experience

### Q1. Tell me about yourself
* **Ans:** (to be filled later)

### Q2. Walk me through your CV
* **Ans:** (to be filled later)

### Q3. What are you currently working on?
* **Ans:** (to be filled later)

### Q4. What is your role at Current organization?
* **Ans:** (to be filled later)

### Q5. What exactly did you contribute in Hyundai Inverter?
* **Ans:** (to be filled later)

### Q6. What exactly did you contribute in Honda EV projects?
* **Ans:** (to be filled later)

### Q7. Why are you looking for a change?
* **Ans:** (to be filled later)

### Q8. Why We?
* **Ans:** (to be filled later)

### Q9. Why Driver Development?
* **Ans:** (to be filled later)

### Q10. Why should we hire you?
* **Ans:** (to be filled later)

---

## 🛠️ Category: Embedded C

### Q11. What is volatile?
* **Ans:** (to be filled later)

### Q12. Why use volatile for registers?
* **Ans:** (to be filled later)

### Q13. Difference between const and volatile?
* **Ans:** (to be filled later)

### Q14. Can a variable be both const and volatile?
* **Ans:** (to be filled later)

### Q15. Difference between static and extern?
* **Ans:** (to be filled later)

### Q16. Difference between global static and local static?
* **Ans:** (to be filled later)

### Q17. Why use extern?
* **Ans:** (to be filled later)

### Q18. What is register storage class?
* **Ans:** (to be filled later)

### Q19. Difference between struct and union?
* **Ans:** (to be filled later)

### Q20. What is structure padding?
* **Ans:** (to be filled later)

### Q21. What is alignment?
* **Ans:** (to be filled later)

### Q22. How do you reduce structure size?
* **Ans:** (to be filled later)

### Q23. What is stack?
* **Ans:** (to be filled later)

### Q24. What is heap?
* **Ans:** (to be filled later)

### Q25. Difference between stack and heap?
* **Ans:** (to be filled later)

### Q26. Memory fragmentation?
* **Ans:** (to be filled later)

### Q27. Memory leak?
* **Ans:** (to be filled later)

### Q28. Stack overflow?
* **Ans:** (to be filled later)

### Q29. Stack corruption?
* **Ans:** (to be filled later)

### Q30. What is pointer arithmetic?
* **Ans:** (to be filled later)

### Q31. Difference between pointer and array?
* **Ans:** (to be filled later)

### Q32. What is a NULL pointer?
* **Ans:** (to be filled later)

### Q33. What is a dangling pointer?
* **Ans:** (to be filled later)

### Q34. What is a wild pointer?
* **Ans:** (to be filled later)

### Q35. What is a double pointer?
* **Ans:** (to be filled later)

### Q36. What is a function pointer?
* **Ans:** (to be filled later)

### Q37. Why use function pointers?
* **Ans:** (to be filled later)

### Q38. Have you used function pointers in state machines?
* **Ans:** (to be filled later)

### Q39. How do you debug function pointer issues?
* **Ans:** (to be filled later)

### Q40. Why would PC jump to an unexpected address?
* **Ans:** (to be filled later)

### Q41. How would you verify a function pointer target?
* **Ans:** (to be filled later)

---

## 🛠️ Category: Build Process

### Q42. What happens during compilation?
* **Ans:** (to be filled later)

### Q43. What does the preprocessor do?
* **Ans:** (to be filled later)

### Q44. What does the compiler do?
* **Ans:** (to be filled later)

### Q45. What does the assembler do?
* **Ans:** (to be filled later)

### Q46. What does the linker do?
* **Ans:** (to be filled later)

### Q47. What is a linker script?
* **Ans:** (to be filled later)

### Q48. Why do we need a linker script?
* **Ans:** (to be filled later)

### Q49. What is a MAP file?
* **Ans:** (to be filled later)

### Q50. How would you use a MAP file during debugging?
* **Ans:** (to be filled later)
---
# Embedded Software Interview Questions & Answers

---

## 🛠️ Category: Startup and Memory Sections

### Q51. What happens after MCU reset?
* **Ans:** (to be filled later)

### Q52. What is startup code?
* **Ans:** (to be filled later)

### Q53. What is the reset handler?
* **Ans:** (to be filled later)

### Q54. What is the vector table?
* **Ans:** (to be filled later)

### Q55. What is reset vector?
* **Ans:** (to be filled later)

### Q56. What is .text?
* **Ans:** (to be filled later)

### Q57. What is .data?
* **Ans:** (to be filled later)

### Q58. What is .bss?
* **Ans:** (to be filled later)

### Q59. What is .rodata?
* **Ans:** (to be filled later)

### Q60. What is stack section?
* **Ans:** (to be filled later)

### Q61. What is heap section?
* **Ans:** (to be filled later)

### Q62. Why is .data copied from Flash to RAM?
* **Ans:** (to be filled later)

### Q63. Why is .bss initialized to zero?
* **Ans:** (to be filled later)

---

## 🛠️ Category: MCU Architecture

### Q64. Explain memory-mapped I/O
* **Ans:** (to be filled later)

### Q65. Explain Harvard architecture
* **Ans:** (to be filled later)

### Q66. Explain Von Neumann architecture
* **Ans:** (to be filled later)

### Q67. Explain endianness
* **Ans:** (to be filled later)

### Q68. Explain little-endian and big-endian
* **Ans:** (to be filled later)

### Q69. What is a memory map?
* **Ans:** (to be filled later)

### Q70. How are peripheral registers accessed?
* **Ans:** (to be filled later)

### Q71. Which Infineon MCUs have you worked on?
* **Ans:** (to be filled later)

### Q72. Explain TC212
* **Ans:** (to be filled later)

### Q73. Explain TC387
* **Ans:** (to be filled later)

### Q74. How did you debug TC212 issues?
* **Ans:** (to be filled later)

---

## 🛠️ Category: Interrupts

### Q75. What is an interrupt?
* **Ans:** (to be filled later)

### Q76. Why interrupts?
* **Ans:** (to be filled later)

### Q77. Polling vs interrupt?
* **Ans:** (to be filled later)

### Q78. Interrupt latency?
* **Ans:** (to be filled later)

### Q79. Interrupt response time?
* **Ans:** (to be filled later)

### Q80. Nested interrupts?
* **Ans:** (to be filled later)

### Q81. What is ISR?
* **Ans:** (to be filled later)

### Q82. What happens when an interrupt occurs?
* **Ans:** (to be filled later)

### Q83. Why should ISR be short?
* **Ans:** (to be filled later)

### Q84. Can malloc be used inside ISR?
* **Ans:** (to be filled later)

### Q85. Can printf be used inside ISR?
* **Ans:** (to be filled later)

### Q86. Can blocking APIs be called from ISR?
* **Ans:** (to be filled later)

### Q87. What is an interrupt vector?
* **Ans:** (to be filled later)

### Q88. What is vector table?
* **Ans:** (to be filled later)

### Q89. How CPU finds ISR?
* **Ans:** (to be filled later)

### Q90. What happens if ISR entry is missing?
* **Ans:** (to be filled later)

### Q91. What happens if ISR address is wrong?
* **Ans:** (to be filled later)

---

## 🛠️ Category: Trap Handler

### Q92. What is Trap Handler?
* **Ans:** (to be filled later)

### Q93. Why does CPU enter Trap Handler?
* **Ans:** (to be filled later)

### Q94. Difference between Trap Handler and ISR?
* **Ans:** (to be filled later)

### Q95. How do you debug Trap Handler?
* **Ans:** (to be filled later)

### Q96. Explain the LIN issue
* **Ans:** (to be filled later)

### Q97. Why was LIN communication not working?
* **Ans:** (to be filled later)

### Q98. How did you find PC entering Trap Handler?
* **Ans:** (to be filled later)

### Q99. Which debugger windows did you use?
* **Ans:** (to be filled later)

### Q100. How did you identify missing vector table entry?
* **Ans:** (to be filled later)

### Q101. What was the root cause?
* **Ans:** (to be filled later)

### Q102. What was the fix?
* **Ans:** (to be filled later)
---

## 🛠️ Category: Device Driver Development

### Q103. What is a device driver?
* **Ans:** (to be filled later)

### Q104. Explain device driver architecture
* **Ans:** (to be filled later)

### Q105. How do you design a device driver?
* **Ans:** (to be filled later)

### Q106. How do you validate a device driver?
* **Ans:** (to be filled later)

### Q107. How do you test a driver?
* **Ans:** (to be filled later)

### Q108. How do you debug a driver?
* **Ans:** (to be filled later)

#### Generic Driver Questions

### Q109. Driver initialization flow?
* **Ans:** (to be filled later)

### Q110. Driver APIs?
* **Ans:** (to be filled later)

### Q111. Register abstraction?
* **Ans:** (to be filled later)

### Q112. Layering?
* **Ans:** (to be filled later)

---

## 🛠️ Category: Register Programming

### Q113. How do you set a bit?
* **Ans:** (to be filled later)

### Q114. How do you clear a bit?
* **Ans:** (to be filled later)

### Q115. How do you toggle a bit?
* **Ans:** (to be filled later)

### Q116. What is read-modify-write?
* **Ans:** (to be filled later)

### Q117. What are reserved bits?
* **Ans:** (to be filled later)

### Q118. Why should reserved bits not be modified?
* **Ans:** (to be filled later)

### Q119. Why are registers volatile?
* **Ans:** (to be filled later)

---

## 🛠️ Category: SPI

### Q120. Explain SPI protocol
* **Ans:** (to be filled later)

### Q121. Explain MOSI
* **Ans:** (to be filled later)

### Q122. Explain MISO
* **Ans:** (to be filled later)

### Q123. Explain SCLK
* **Ans:** (to be filled later)

### Q124. Explain Chip Select
* **Ans:** (to be filled later)

### Q125. Explain Master/Slave
* **Ans:** (to be filled later)

### Q126. Explain Full Duplex
* **Ans:** (to be filled later)

### Q127. Explain CPOL
* **Ans:** (to be filled later)

### Q128. Explain CPHA
* **Ans:** (to be filled later)

### Q129. Explain SPI Modes
* **Ans:** (to be filled later)

#### Driver Questions

### Q130. How do you write an SPI driver?
* **Ans:** (to be filled later)

### Q131. Polling SPI vs Interrupt SPI?
* **Ans:** (to be filled later)

### Q132. DMA SPI?
* **Ans:** (to be filled later)

#### Debugging

### Q133. SPI not working, what do you check?
* **Ans:** (to be filled later)

### Q134. How do you debug SPI?
* **Ans:** (to be filled later)

### Q135. How do you use logic analyzer for SPI?
* **Ans:** (to be filled later)

#### Your Project

### Q136. Explain SPI implementation on WCT2013
* **Ans:** (to be filled later)

### Q137. Which registers did you configure?
* **Ans:** (to be filled later)
---
# Embedded Software Interview Questions & Answers

---

## 🛠️ Category: I2C

### Q138. Explain I2C
* **Ans:** (to be filled later)

### Q139. What are SDA and SCL?
* **Ans:** (to be filled later)

### Q140. What is Start Condition?
* **Ans:** (to be filled later)

### Q141. What is Stop Condition?
* **Ans:** (to be filled later)

### Q142. What is ACK?
* **Ans:** (to be filled later)

### Q143. What is NACK?
* **Ans:** (to be filled later)

### Q144. What is Arbitration?
* **Ans:** (to be filled later)

### Q145. What is Clock Stretching?
* **Ans:** (to be filled later)

### Q146. Multi-master I2C?
* **Ans:** (to be filled later)

### Q147. How do you debug I2C?
* **Ans:** (to be filled later)

---

## 🛠️ Category: UART

### Q148. Explain UART
* **Ans:** (to be filled later)

### Q149. Explain UART Frame
* **Ans:** (to be filled later)

### Q150. What is Baud Rate?
* **Ans:** (to be filled later)

### Q151. What is Parity?
* **Ans:** (to be filled later)

### Q152. What is Framing Error?
* **Ans:** (to be filled later)

### Q153. What is Overrun Error?
* **Ans:** (to be filled later)

### Q154. Interrupt UART?
* **Ans:** (to be filled later)

### Q155. Polling UART?
* **Ans:** (to be filled later)

### Q156. How do you debug UART?
* **Ans:** (to be filled later)

---

## 🛠️ Category: LIN

### Q157. Explain LIN architecture
* **Ans:** (to be filled later)

### Q158. Explain LIN frame structure
* **Ans:** (to be filled later)

### Q159. Explain Break Field
* **Ans:** (to be filled later)

### Q160. Explain Sync Field
* **Ans:** (to be filled later)

### Q161. Explain PID
* **Ans:** (to be filled later)

### Q162. Explain Data Field
* **Ans:** (to be filled later)

### Q163. Explain Checksum
* **Ans:** (to be filled later)

### Q164. Difference between Classic and Enhanced Checksum
* **Ans:** (to be filled later)

### Q165. LIN Master vs LIN Slave
* **Ans:** (to be filled later)

### Q166. Explain LIN Scheduler
* **Ans:** (to be filled later)

### Q167. Explain AutoBaud
* **Ans:** (to be filled later)

### Q168. Explain Sleep/Wakeup
* **Ans:** (to be filled later)

#### Driver Questions

### Q169. How did you implement LIN driver?
* **Ans:** (to be filled later)

### Q170. What modules did you write?
* **Ans:** (to be filled later)

### Q171. How did you validate LIN?
* **Ans:** (to be filled later)

#### Testing

### Q172. Explain LIN conformance testing
* **Ans:** (to be filled later)

### Q173. How did you use CANoe?
* **Ans:** (to be filled later)

---

## 🛠️ Category: CAN

### Q174. Explain CAN
* **Ans:** (to be filled later)

### Q175. Explain CAN architecture
* **Ans:** (to be filled later)

### Q176. Explain CAN frame
* **Ans:** (to be filled later)

### Q177. Standard CAN vs Extended CAN
* **Ans:** (to be filled later)

### Q178. Explain Arbitration
* **Ans:** (to be filled later)

### Q179. Why lower ID wins?
* **Ans:** (to be filled later)

### Q180. Explain Bus-Off
* **Ans:** (to be filled later)

### Q181. Explain Error Frame
* **Ans:** (to be filled later)

### Q182. Explain CAN FD
* **Ans:** (to be filled later)

### Q183. Explain CAN Controller
* **Ans:** (to be filled later)

### Q184. Explain CAN Transceiver
* **Ans:** (to be filled later)

#### Debugging

### Q185. How do you debug CAN?
* **Ans:** (to be filled later)

### Q186. How do you use CANoe?
* **Ans:** (to be filled later)

### Q187. What if CAN communication fails?
* **Ans:** (to be filled later)

#### AUTOSAR

### Q188. Explain CAN Driver
* **Ans:** (to be filled later)

### Q189. Explain CANIF
* **Ans:** (to be filled later)

### Q190. Explain your CANIF work
* **Ans:** (to be filled later)

---

## 🛠️ Category: ADC

### Q191. What is ADC?
* **Ans:** (to be filled later)

### Q192. ADC resolution?
* **Ans:** (to be filled later)

### Q193. 10-bit vs 12-bit ADC?
* **Ans:** (to be filled later)

### Q194. ADC sampling time?
* **Ans:** (to be filled later)

### Q195. ADC conversion time?
* **Ans:** (to be filled later)

### Q196. ADC interrupt mode?
* **Ans:** (to be filled later)

### Q197. ADC DMA mode?
* **Ans:** (to be filled later)

### Q198. ADC calibration?
* **Ans:** (to be filled later)

### Q199. How would you validate ADC?
* **Ans:** (to be filled later)

---

## 🛠️ Category: GPIO

### Q200. What is GPIO?
* **Ans:** (to be filled later)

### Q201. Input mode?
* **Ans:** (to be filled later)

### Q202. Output mode?
* **Ans:** (to be filled later)

### Q203. Pull-up?
* **Ans:** (to be filled later)

### Q204. Pull-down?
* **Ans:** (to be filled later)

### Q205. Open Drain?
* **Ans:** (to be filled later)

### Q206. Push Pull?
* **Ans:** (to be filled later)

### Q207. GPIO interrupt?
* **Ans:** (to be filled later)
---
# Embedded Software Interview Questions & Answers

---

## 🛠️ Category: Timers

### Q208. What is a timer?
* **Ans:** (to be filled later)

### Q209. Prescaler?
* **Ans:** (to be filled later)

### Q210. Compare mode?
* **Ans:** (to be filled later)

### Q211. Capture mode?
* **Ans:** (to be filled later)

### Q212. Timer interrupt?
* **Ans:** (to be filled later)

### Q213. How do you generate periodic interrupts?
* **Ans:** (to be filled later)

---

## 🛠️ Category: PWM

### Q214. What is PWM?
* **Ans:** (to be filled later)

### Q215. What is duty cycle?
* **Ans:** (to be filled later)

### Q216. What is PWM frequency?
* **Ans:** (to be filled later)

### Q217. How is PWM generated?
* **Ans:** (to be filled later)

### Q218. PWM applications?
* **Ans:** (to be filled later)

---

## 🛠️ Category: Flash

### Q219. Explain Flash memory
* **Ans:** (to be filled later)

### Q220. Why erase before programming?
* **Ans:** (to be filled later)

### Q221. What is sector erase?
* **Ans:** (to be filled later)

### Q222. What is Flash endurance?
* **Ans:** (to be filled later)

### Q223. What is wear leveling?
* **Ans:** (to be filled later)

### Q224. Flash driver architecture?
* **Ans:** (to be filled later)

### Q225. How do you validate Flash writes?
* **Ans:** (to be filled later)

---

## 🛠️ Category: EEPROM

### Q226. EEPROM vs Flash?
* **Ans:** (to be filled later)

### Q227. EEPROM endurance?
* **Ans:** (to be filled later)

### Q228. EEPROM driver design?
* **Ans:** (to be filled later)

---

## 🛠️ Category: DMA

### Q229. What is DMA?
* **Ans:** (to be filled later)

### Q230. Why use DMA?
* **Ans:** (to be filled later)

### Q231. DMA vs Interrupt?
* **Ans:** (to be filled later)

### Q232. DMA vs Polling?
* **Ans:** (to be filled later)

### Q233. SPI + DMA?
* **Ans:** (to be filled later)

### Q234. ADC + DMA?
* **Ans:** (to be filled later)

### Q235. DMA debugging?
* **Ans:** (to be filled later)

---

## 🛠️ Category: Debugging

### Q236. Explain your debugging methodology
* **Ans:** (to be filled later)

### Q237. How do you debug a hang?
* **Ans:** (to be filled later)

### Q238. How do you debug a crash?
* **Ans:** (to be filled later)

### Q239. How do you debug memory corruption?
* **Ans:** (to be filled later)

### Q240. How do you debug watchdog reset?
* **Ans:** (to be filled later)

### Q241. How do you debug stack overflow?
* **Ans:** (to be filled later)

### Q242. How do you debug function pointer corruption?
* **Ans:** (to be filled later)

#### Debugger Usage

### Q243. Watch Window?
* **Ans:** (to be filled later)

### Q244. Memory Window?
* **Ans:** (to be filled later)

### Q245. Registers Window?
* **Ans:** (to be filled later)

### Q246. Call Stack?
* **Ans:** (to be filled later)

### Q247. Breakpoints?
* **Ans:** (to be filled later)

---

## 🛠️ Category: AUTOSAR

### Q248. Explain AUTOSAR architecture
* **Ans:** (to be filled later)

### Q249. Why AUTOSAR?
* **Ans:** (to be filled later)

### Q250. Explain Application Layer
* **Ans:** (to be filled later)

### Q251. Explain RTE
* **Ans:** (to be filled later)

### Q252. Explain BSW
* **Ans:** (to be filled later)

### Q253. Explain MCAL
* **Ans:** (to be filled later)

### Q254. Explain DIO Driver
* **Ans:** (to be filled later)

### Q255. Explain CAN Driver
* **Ans:** (to be filled later)

### Q256. Explain SPI Driver
* **Ans:** (to be filled later)

### Q257. Explain ADC Driver
* **Ans:** (to be filled later)

### Q258. Explain GPT Driver
* **Ans:** (to be filled later)

#### CDD

### Q259. What is CDD?
* **Ans:** (to be filled later)

### Q260. Why use CDD?
* **Ans:** (to be filled later)

### Q261. Explain your GDIC/PMIC CDD work
* **Ans:** (to be filled later)

#### EB Tresos

### Q262. What is EB Tresos?
* **Ans:** (to be filled later)

### Q263. What configurations have you done?
* **Ans:** (to be filled later)
---

## 🛠️ Category: Functional Safety

### Q264. What is ISO26262?
* **Ans:** (to be filled later)

### Q265. What is Functional Safety?
* **Ans:** (to be filled later)

### Q266. What is HARA?
* **Ans:** (to be filled later)

### Q267. What is ASIL?
* **Ans:** (to be filled later)

### Q268. ASIL A/B/C/D?
* **Ans:** (to be filled later)

### Q269. What is a Safety Goal?
* **Ans:** (to be filled later)

### Q270. What is Traceability?
* **Ans:** (to be filled later)

### Q271. What is FMEA?
* **Ans:** (to be filled later)

### Q272. What is FTA?
* **Ans:** (to be filled later)

#### Your Project

### Q273. Explain Hyundai Inverter
* **Ans:** (to be filled later)

### Q274. Explain FUSA Gap Analysis
* **Ans:** (to be filled later)

### Q275. Explain SWAD
* **Ans:** (to be filled later)

### Q276. Explain SADD
* **Ans:** (to be filled later)

---

## 🛠️ Category: MISRA C

### Q277. What is MISRA C?
* **Ans:** (to be filled later)

### Q278. Why MISRA?
* **Ans:** (to be filled later)

### Q279. Common MISRA violations?
* **Ans:** (to be filled later)

### Q280. Why avoid dynamic memory?
* **Ans:** (to be filled later)

### Q281. Why avoid unrestricted pointer casting?
* **Ans:** (to be filled later)

### Q282. How do you perform static analysis?
* **Ans:** (to be filled later)

---

## 🛠️ Category: Bootloader

### Q283. What is a bootloader?
* **Ans:** (to be filled later)

### Q284. Why bootloader?
* **Ans:** (to be filled later)

### Q285. Bootloader vs Application?
* **Ans:** (to be filled later)

### Q286. Explain firmware update flow
* **Ans:** (to be filled later)

### Q287. Explain secure firmware update
* **Ans:** (to be filled later)

### Q288. Have you worked on bootloader integration?
* **Ans:** (to be filled later)

---

## 🛠️ Category: Secure Boot / Cybersecurity

### Q289. What is Secure Boot?
* **Ans:** (to be filled later)

### Q290. What is HSM?
* **Ans:** (to be filled later)

### Q291. What is TrustZone?
* **Ans:** (to be filled later)

### Q292. What is Firmware Authentication?
* **Ans:** (to be filled later)

### Q293. What is Secure Firmware Update?
* **Ans:** (to be filled later)

---

## 🛠️ Category: Leadership / Staff Engineer

### Q294. Most difficult bug you solved?
* **Ans:** (to be filled later)

### Q295. Biggest technical challenge?
* **Ans:** (to be filled later)

### Q296. Customer escalation you handled?
* **Ans:** (to be filled later)

### Q297. How do you mentor engineers?
* **Ans:** (to be filled later)

### Q298. How do you conduct code reviews?
* **Ans:** (to be filled later)

### Q299. How do you estimate effort?
* **Ans:** (to be filled later)

### Q300. How do you handle technical disagreements?
* **Ans:** (to be filled later)

### Q301. What makes you suitable for Staff Engineer?
* **Ans:** (to be filled later)
---
# Final Night-Before Priority (Top 30)

---

### Q302. Tell me about yourself
* **Ans:** (to be filled later)

### Q303. LIN Driver
* **Ans:** (to be filled later)

### Q304. LIN Frame
* **Ans:** (to be filled later)

### Q305. LIN Checksum
* **Ans:** (to be filled later)

### Q306. CAN
* **Ans:** (to be filled later)

### Q307. CAN Arbitration
* **Ans:** (to be filled later)

### Q308. CANIF
* **Ans:** (to be filled later)

### Q309. MCAL
* **Ans:** (to be filled later)

### Q310. CDD
* **Ans:** (to be filled later)

### Q311. SPI
* **Ans:** (to be filled later)

### Q312. UART
* **Ans:** (to be filled later)

### Q313. Interrupt Flow
* **Ans:** (to be filled later)

### Q314. Vector Table
* **Ans:** (to be filled later)

### Q315. ISR
* **Ans:** (to be filled later)

### Q316. Trap Handler
* **Ans:** (to be filled later)

### Q317. Missing ISR Entry RCA
* **Ans:** (to be filled later)

### Q318. volatile
* **Ans:** (to be filled later)

### Q319. Function Pointer
* **Ans:** (to be filled later)

### Q320. Startup Code
* **Ans:** (to be filled later)

### Q321. Linker Script
* **Ans:** (to be filled later)

### Q322. Memory Sections
* **Ans:** (to be filled later)

### Q323. Device Driver Architecture
* **Ans:** (to be filled later)

### Q324. TC212 Experience
* **Ans:** (to be filled later)

### Q325. Hyundai FUSA Work
* **Ans:** (to be filled later)

### Q326. MISRA C
* **Ans:** (to be filled later)

### Q327. Flash Basics
* **Ans:** (to be filled later)

### Q328. DMA
* **Ans:** (to be filled later)

### Q329. Debugging Methodology
* **Ans:** (to be filled later)

### Q330. Why We
* **Ans:** (to be filled later)

### Q331. Why You
* **Ans:** (to be filled later)

---
```



