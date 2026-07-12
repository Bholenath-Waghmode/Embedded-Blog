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
# 🐧 Embedded Engineering Q&A Vault

<!-- 
  AUTOMATED LEFT-SIDE FLOATING NAVIGATION MENU
  Use standard text asterisks (*) and spaces to indent your sub-questions.
  Make sure your (#links) are all lowercase, with dashes instead of spaces.
   Look at this Example:Your Heading inside Embedded-BlogQAns.md: ### Q2. What is a Spinlock?How GitHub creates the hidden ID: q2-what-is-a-spinlockYour exact link inside Embedded-Blog.md: [Q2. What is a Spinlock?](Embedded-BlogQAns.md#q2-what-is-a-spinlock)
-->
# Embedded Software Interview Questions List
---
* **Generic:**
  * Questions Answers:
    * [Q1. What's Volatile?](Embedded-BlogQAns.md#q1-whats-volatile)
* **Device Driver:**
  * Questions Answers:
    * [Q1. What's a Device Driver?](Embedded-BlogQAns.md#q1-whats-a-device-driver)
---

## 1. Introduction & Experience
* [Q1. Tell me about yourself](Embedded-BlogQAns.md#q1-tell-me-about-yourself)
* [Q2. Walk me through your CV](Embedded-BlogQAns.md#q2-walk-me-through-your-cv)
* [Q3. What are you currently working on?](Embedded-BlogQAns.md#q3-what-are-you-currently-working-on)
* [Q4. What is your role at Current organization?](Embedded-BlogQAns.md#q4-what-is-your-role-at-Current-organization)
* [Q5. What exactly did you contribute in Hyundai Inverter?](Embedded-BlogQAns.md#q5-what-exactly-did-you-contribute-in-hyundai-inverter)
* [Q6. What exactly did you contribute in Honda EV projects?](Embedded-BlogQAns.md#q6-what-exactly-did-you-contribute-in-honda-ev-projects)
* [Q7. Why are you looking for a change?](Embedded-BlogQAns.md#q7-why-are-you-looking-for-a-change)
* [Q8. Why We?](Embedded-BlogQAns.md#q8-why-We)
* [Q9. Why Driver Development?](Embedded-BlogQAns.md#q9-why-driver-development)
* [Q10. Why should we hire you?](Embedded-BlogQAns.md#q10-why-should-we-hire-you)

## 2. Embedded C
* [Q11. What is volatile?](Embedded-BlogQAns.md#q11-what-is-volatile)
* [Q12. Why use volatile for registers?](Embedded-BlogQAns.md#q12-why-use-volatile-for-registers)
* [Q13. Difference between const and volatile?](Embedded-BlogQAns.md#q13-difference-between-const-and-volatile)
* [Q14. Can a variable be both const and volatile?](Embedded-BlogQAns.md#q14-can-a-variable-be-both-const-and-volatile)
* [Q15. Difference between static and extern?](Embedded-BlogQAns.md#q15-difference-between-static-and-extern)
* [Q16. Difference between global static and local static?](Embedded-BlogQAns.md#q16-difference-between-global-static-and-local-static)
* [Q17. Why use extern?](Embedded-BlogQAns.md#q17-why-use-extern)
* [Q18. What is register storage class?](Embedded-BlogQAns.md#q18-what-is-register-storage-class)
* [Q19. Difference between struct and union?](Embedded-BlogQAns.md#q19-difference-between-struct-and-union)
* [Q20. What is structure padding?](Embedded-BlogQAns.md#q20-what-is-structure-padding)
* [Q21. What is alignment?](Embedded-BlogQAns.md#q21-what-is-alignment)
* [Q22. How do you reduce structure size?](Embedded-BlogQAns.md#q22-how-do-you-reduce-structure-size)
* [Q23. What is stack?](Embedded-BlogQAns.md#q23-what-is-stack)
* [Q24. What is heap?](Embedded-BlogQAns.md#q24-what-is-heap)
* [Q25. Difference between stack and heap?](Embedded-BlogQAns.md#q25-difference-between-stack-and-heap)
* [Q26. Memory fragmentation?](Embedded-BlogQAns.md#q26-memory-fragmentation)
* [Q27. Memory leak?](Embedded-BlogQAns.md#q27-memory-leak)
* [Q28. Stack overflow?](Embedded-BlogQAns.md#q28-stack-overflow)
* [Q29. Stack corruption?](Embedded-BlogQAns.md#q29-stack-corruption)
* [Q30. What is pointer arithmetic?](Embedded-BlogQAns.md#q30-what-is-pointer-arithmetic)
* [Q31. Difference between pointer and array?](Embedded-BlogQAns.md#q31-difference-between-pointer-and-array)
* [Q32. What is a NULL pointer?](Embedded-BlogQAns.md#q32-what-is-a-null-pointer)
* [Q33. What is a dangling pointer?](Embedded-BlogQAns.md#q33-what-is-a-dangling-pointer)
* [Q34. What is a wild pointer?](Embedded-BlogQAns.md#q34-what-is-a-wild-pointer)
* [Q35. What is a double pointer?](Embedded-BlogQAns.md#q35-what-is-a-double-pointer)
* [Q36. What is a function pointer?](Embedded-BlogQAns.md#q36-what-is-a-function-pointer)
* [Q37. Why use function pointers?](Embedded-BlogQAns.md#q37-why-use-function-pointers)
* [Q38. Have you used function pointers in state machines?](Embedded-BlogQAns.md#q38-have-you-used-function-pointers-in-state-machines)
* [Q39. How do you debug function pointer issues?](Embedded-BlogQAns.md#q39-how-do-you-debug-function-pointer-issues)
* [Q40. Why would PC jump to an unexpected address?](Embedded-BlogQAns.md#q40-why-would-pc-jump-to-an-unexpected-address)
* [Q41. How would you verify a function pointer target?](Embedded-BlogQAns.md#q41-how-would-you-verify-a-function-pointer-target)

## 3. Build Process
* [Q42. What happens during compilation?](Embedded-BlogQAns.md#q42-what-happens-during-compilation)
* [Q43. What does the preprocessor do?](Embedded-BlogQAns.md#q43-what-does-the-preprocessor-do)
* [Q44. What does the compiler do?](Embedded-BlogQAns.md#q44-what-does-the-compiler-do)
* [Q45. What does the assembler do?](Embedded-BlogQAns.md#q45-what-does-the-assembler-do)
* [Q46. What does the linker do?](Embedded-BlogQAns.md#q46-what-does-the-linker-do)
* [Q47. What is a linker script?](Embedded-BlogQAns.md#q47-what-is-a-linker-script)
* [Q48. Why do we need a linker script?](Embedded-BlogQAns.md#q48-why-do-we-need-a-linker-script)
* [Q49. What is a MAP file?](Embedded-BlogQAns.md#q49-what-is-a-map-file)
* [Q50. How would you use a MAP file during debugging?](Embedded-BlogQAns.md#q50-how-would-you-use-a-map-file-during-debugging)
---

## 4. Startup and Memory Sections
* [Q51. What happens after MCU reset?](Embedded-BlogQAns.md#q51-what-happens-after-mcu-reset)
* [Q52. What is startup code?](Embedded-BlogQAns.md#q52-what-is-startup-code)
* [Q53. What is the reset handler?](Embedded-BlogQAns.md#q53-what-is-the-reset-handler)
* [Q54. What is the vector table?](Embedded-BlogQAns.md#q54-what-is-the-vector-table)
* [Q55. What is reset vector?](Embedded-BlogQAns.md#q55-what-is-reset-vector)
* [Q56. What is .text?](Embedded-BlogQAns.md#q56-what-is-text)
* [Q57. What is .data?](Embedded-BlogQAns.md#q57-what-is-data)
* [Q58. What is .bss?](Embedded-BlogQAns.md#q58-what-is-bss)
* [Q59. What is .rodata?](Embedded-BlogQAns.md#q59-what-is-rodata)
* [Q60. What is stack section?](Embedded-BlogQAns.md#q60-what-is-stack-section)
* [Q61. What is heap section?](Embedded-BlogQAns.md#q61-what-is-heap-section)
* [Q62. Why is .data copied from Flash to RAM?](Embedded-BlogQAns.md#q62-why-is-data-copied-from-flash-to-ram)
* [Q63. Why is .bss initialized to zero?](Embedded-BlogQAns.md#q63-why-is-bss-initialized-to-zero)

## 5. MCU Architecture
* [Q64. Explain memory-mapped I/O](Embedded-BlogQAns.md#q64-explain-memory-mapped-io)
* [Q65. Explain Harvard architecture](Embedded-BlogQAns.md#q65-explain-harvard-architecture)
* [Q66. Explain Von Neumann architecture](Embedded-BlogQAns.md#q66-explain-von-neumann-architecture)
* [Q67. Explain endianness](Embedded-BlogQAns.md#q67-explain-endianness)
* [Q68. Explain little-endian and big-endian](Embedded-BlogQAns.md#q68-explain-little-endian-and-big-endian)
* [Q69. What is a memory map?](Embedded-BlogQAns.md#q69-what-is-a-memory-map)
* [Q70. How are peripheral registers accessed?](Embedded-BlogQAns.md#q70-how-are-peripheral-registers-accessed)
* [Q71. Which Infineon MCUs have you worked on?](Embedded-BlogQAns.md#q71-which-infineon-mcus-have-you-worked-on)
* [Q72. Explain TC212](Embedded-BlogQAns.md#q72-explain-tc212)
* [Q73. Explain TC387](Embedded-BlogQAns.md#q73-explain-tc387)
* [Q74. How did you debug TC212 issues?](Embedded-BlogQAns.md#q74-how-did-you-debug-tc212-issues)

## 6. Interrupts
* [Q75. What is an interrupt?](Embedded-BlogQAns.md#q75-what-is-an-interrupt)
* [Q76. Why interrupts?](Embedded-BlogQAns.md#q76-why-interrupts)
* [Q77. Polling vs interrupt?](Embedded-BlogQAns.md#q77-polling-vs-interrupt)
* [Q78. Interrupt latency?](Embedded-BlogQAns.md#q78-interrupt-latency)
* [Q79. Interrupt response time?](Embedded-BlogQAns.md#q79-interrupt-response-time)
* [Q80. Nested interrupts?](Embedded-BlogQAns.md#q80-nested-interrupts)
* [Q81. What is ISR?](Embedded-BlogQAns.md#q81-what-is-isr)
* [Q82. What happens when an interrupt occurs?](Embedded-BlogQAns.md#q82-what-happens-when-an-interrupt-occurs)
* [Q83. Why should ISR be short?](Embedded-BlogQAns.md#q83-why-should-isr-be-short)
* [Q84. Can malloc be used inside ISR?](Embedded-BlogQAns.md#q84-can-malloc-be-used-inside-isr)
* [Q85. Can printf be used inside ISR?](Embedded-BlogQAns.md#q85-can-printf-be-used-inside-isr)
* [Q86. Can blocking APIs be called from ISR?](Embedded-BlogQAns.md#q86-can-blocking-apis-be-called-from-isr)
* [Q87. What is an interrupt vector?](Embedded-BlogQAns.md#q87-what-is-an-interrupt-vector)
* [Q88. What is vector table?](Embedded-BlogQAns.md#q88-what-is-vector-table)
* [Q89. How CPU finds ISR?](Embedded-BlogQAns.md#q89-how-cpu-finds-isr)
* [Q90. What happens if ISR entry is missing?](Embedded-BlogQAns.md#q90-what-happens-if-isr-entry-is-missing)
* [Q91. What happens if ISR address is wrong?](Embedded-BlogQAns.md#q91-what-happens-if-isr-address-is-wrong)

## 7. Trap Handler
* [Q92. What is Trap Handler?](Embedded-BlogQAns.md#q92-what-is-trap-handler)
* [Q93. Why does CPU enter Trap Handler?](Embedded-BlogQAns.md#q93-why-does-cpu-enter-trap-handler)
* [Q94. Difference between Trap Handler and ISR?](Embedded-BlogQAns.md#q94-difference-between-trap-handler-and-isr)
* [Q95. How do you debug Trap Handler?](Embedded-BlogQAns.md#q95-how-do-you-debug-trap-handler)
* [Q96. Explain the LIN issue](Embedded-BlogQAns.md#q96-explain-the-lin-issue)
* [Q97. Why was LIN communication not working?](Embedded-BlogQAns.md#q97-why-was-lin-communication-not-working)
* [Q98. How did you find PC entering Trap Handler?](Embedded-BlogQAns.md#q98-how-did-you-find-pc-entering-trap-handler)
* [Q99. Which debugger windows did you use?](Embedded-BlogQAns.md#q99-which-debugger-windows-did-you-use)
* [Q100. How did you identify missing vector table entry?](Embedded-BlogQAns.md#q100-how-did-you-identify-missing-vector-table-entry)
* [Q101. What was the root cause?](Embedded-BlogQAns.md#q101-what-was-the-root-cause)
* [Q102. What was the fix?](Embedded-BlogQAns.md#q102-what-was-the-fix)
---
# Embedded Software Interview Questions List

## 8. Device Driver Development
* [Q103. What is a device driver?](Embedded-BlogQAns.md#q103-what-is-a-device-driver)
* [Q104. Explain device driver architecture](Embedded-BlogQAns.md#q104-explain-device-driver-architecture)
* [Q105. How do you design a device driver?](Embedded-BlogQAns.md#q105-how-do-you-design-a-device-driver)
* [Q106. How do you validate a device driver?](Embedded-BlogQAns.md#q106-how-do-you-validate-a-device-driver)
* [Q107. How do you test a driver?](Embedded-BlogQAns.md#q107-how-do-you-test-a-driver)
* [Q108. How do you debug a driver?](Embedded-BlogQAns.md#q108-how-do-you-debug-a-driver)

### Generic Driver Questions
* [Q109. Driver initialization flow?](Embedded-BlogQAns.md#q109-driver-initialization-flow)
* [Q110. Driver APIs?](Embedded-BlogQAns.md#q110-driver-apis)
* [Q111. Register abstraction?](Embedded-BlogQAns.md#q111-register-abstraction)
* [Q112. Layering?](Embedded-BlogQAns.md#q112-layering)

## 9. Register Programming
* [Q113. How do you set a bit?](Embedded-BlogQAns.md#q113-how-do-you-set-a-bit)
* [Q114. How do you clear a bit?](Embedded-BlogQAns.md#q114-how-do-you-clear-a-bit)
* [Q115. How do you toggle a bit?](Embedded-BlogQAns.md#q115-how-do-you-toggle-a-bit)
* [Q116. What is read-modify-write?](Embedded-BlogQAns.md#q116-what-is-read-modify-write)
* [Q117. What are reserved bits?](Embedded-BlogQAns.md#q117-what-are-reserved-bits)
* [Q118. Why should reserved bits not be modified?](Embedded-BlogQAns.md#q118-why-should-reserved-bits-not-be-modified)
* [Q119. Why are registers volatile?](Embedded-BlogQAns.md#q119-why-are-registers-volatile)

## 10. SPI
* [Q120. Explain SPI protocol](Embedded-BlogQAns.md#q120-explain-spi-protocol)
* [Q121. Explain MOSI](Embedded-BlogQAns.md#q121-explain-mosi)
* [Q122. Explain MISO](Embedded-BlogQAns.md#q122-explain-miso)
* [Q123. Explain SCLK](Embedded-BlogQAns.md#q123-explain-sclk)
* [Q124. Explain Chip Select](Embedded-BlogQAns.md#q124-explain-chip-select)
* [Q125. Explain Master/Slave](Embedded-BlogQAns.md#q125-explain-masterslave)
* [Q126. Explain Full Duplex](Embedded-BlogQAns.md#q126-explain-full-duplex)
* [Q127. Explain CPOL](Embedded-BlogQAns.md#q127-explain-cpol)
* [Q128. Explain CPHA](Embedded-BlogQAns.md#q128-explain-cpha)
* [Q129. Explain SPI Modes](Embedded-BlogQAns.md#q129-explain-spi-modes)

### Driver Questions
* [Q130. How do you write an SPI driver?](Embedded-BlogQAns.md#q130-how-do-you-write-an-spi-driver)
* [Q131. Polling SPI vs Interrupt SPI?](Embedded-BlogQAns.md#q131-polling-spi-vs-interrupt-spi)
* [Q132. DMA SPI?](Embedded-BlogQAns.md#q132-dma-spi)

### Debugging
* [Q133. SPI not working, what do you check?](Embedded-BlogQAns.md#q133-spi-not-working-what-do-you-check)
* [Q134. How do you debug SPI?](Embedded-BlogQAns.md#q134-how-do-you-debug-spi)
* [Q135. How do you use logic analyzer for SPI?](Embedded-BlogQAns.md#q135-how-do-you-use-logic-analyzer-for-spi)

### Your Project
* [Q136. Explain SPI implementation on WCT2013](Embedded-BlogQAns.md#q136-explain-spi-implementation-on-wct2013)
* [Q137. Which registers did you configure?](Embedded-BlogQAns.md#q137-which-registers-did-you-configure)
---
# Embedded Software Interview Questions List

## 11. I2C
* [Q138. Explain I2C](Embedded-BlogQAns.md#q138-explain-i2c)
* [Q139. What are SDA and SCL?](Embedded-BlogQAns.md#q139-what-are-sda-and-scl)
* [Q140. What is Start Condition?](Embedded-BlogQAns.md#q140-what-is-start-condition)
* [Q141. What is Stop Condition?](Embedded-BlogQAns.md#q141-what-is-stop-condition)
* [Q142. What is ACK?](Embedded-BlogQAns.md#q142-what-is-ack)
* [Q143. What is NACK?](Embedded-BlogQAns.md#q143-what-is-nack)
* [Q144. What is Arbitration?](Embedded-BlogQAns.md#q144-what-is-arbitration)
* [Q145. What is Clock Stretching?](Embedded-BlogQAns.md#q145-what-is-clock-stretching)
* [Q146. Multi-master I2C?](Embedded-BlogQAns.md#q146-multi-master-i2c)
* [Q147. How do you debug I2C?](Embedded-BlogQAns.md#q147-how-do-you-debug-i2c)

## 12. UART
* [Q148. Explain UART](Embedded-BlogQAns.md#q148-explain-uart)
* [Q149. Explain UART Frame](Embedded-BlogQAns.md#q149-explain-uart-frame)
* [Q150. What is Baud Rate?](Embedded-BlogQAns.md#q150-what-is-baud-rate)
* [Q151. What is Parity?](Embedded-BlogQAns.md#q151-what-is-parity)
* [Q152. What is Framing Error?](Embedded-BlogQAns.md#q152-what-is-framing-error)
* [Q153. What is Overrun Error?](Embedded-BlogQAns.md#q153-what-is-overrun-error)
* [Q154. Interrupt UART?](Embedded-BlogQAns.md#q154-interrupt-uart)
* [Q155. Polling UART?](Embedded-BlogQAns.md#q155-polling-uart)
* [Q156. How do you debug UART?](Embedded-BlogQAns.md#q156-how-do-you-debug-uart)

## 13. LIN
* [Q157. Explain LIN architecture](Embedded-BlogQAns.md#q157-explain-lin-architecture)
* [Q158. Explain LIN frame structure](Embedded-BlogQAns.md#q158-explain-lin-frame-structure)
* [Q159. Explain Break Field](Embedded-BlogQAns.md#q159-explain-break-field)
* [Q160. Explain Sync Field](Embedded-BlogQAns.md#q160-explain-sync-field)
* [Q161. Explain PID](Embedded-BlogQAns.md#q161-explain-pid)
* [Q162. Explain Data Field](Embedded-BlogQAns.md#q162-explain-data-field)
* [Q163. Explain Checksum](Embedded-BlogQAns.md#q163-explain-checksum)
* [Q164. Difference between Classic and Enhanced Checksum](Embedded-BlogQAns.md#q164-difference-between-classic-and-enhanced-checksum)
* [Q165. LIN Master vs LIN Slave](Embedded-BlogQAns.md#q165-lin-master-vs-lin-slave)
* [Q166. Explain LIN Scheduler](Embedded-BlogQAns.md#q166-explain-lin-scheduler)
* [Q167. Explain AutoBaud](Embedded-BlogQAns.md#q167-explain-autobaud)
* [Q168. Explain Sleep/Wakeup](Embedded-BlogQAns.md#q168-explain-sleepwakeup)

### Driver Questions
* [Q169. How did you implement LIN driver?](Embedded-BlogQAns.md#q169-how-did-you-implement-lin-driver)
* [Q170. What modules did you write?](Embedded-BlogQAns.md#q170-what-modules-did-you-write)
* [Q171. How did you validate LIN?](Embedded-BlogQAns.md#q171-how-did-you-validate-lin)

### Testing
* [Q172. Explain LIN conformance testing](Embedded-BlogQAns.md#q172-explain-lin-conformance-testing)
* [Q173. How did you use CANoe?](Embedded-BlogQAns.md#q173-how-did-you-use-canoe)

## 14. CAN
* [Q174. Explain CAN](Embedded-BlogQAns.md#q174-explain-can)
* [Q175. Explain CAN architecture](Embedded-BlogQAns.md#q175-explain-can-architecture)
* [Q176. Explain CAN frame](Embedded-BlogQAns.md#q176-explain-can-frame)
* [Q177. Standard CAN vs Extended CAN](Embedded-BlogQAns.md#q177-standard-can-vs-extended-can)
* [Q178. Explain Arbitration](Embedded-BlogQAns.md#q178-explain-arbitration)
* [Q179. Why lower ID wins?](Embedded-BlogQAns.md#q179-why-lower-id-wins)
* [Q180. Explain Bus-Off](Embedded-BlogQAns.md#q180-explain-bus-off)
* [Q181. Explain Error Frame](Embedded-BlogQAns.md#q181-explain-error-frame)
* [Q182. Explain CAN FD](Embedded-BlogQAns.md#q182-explain-can-fd)
* [Q183. Explain CAN Controller](Embedded-BlogQAns.md#q183-explain-can-controller)
* [Q184. Explain CAN Transceiver](Embedded-BlogQAns.md#q184-explain-can-transceiver)

### Debugging
* [Q185. How do you debug CAN?](Embedded-BlogQAns.md#q185-how-do-you-debug-can)
* [Q186. How do you use CANoe?](Embedded-BlogQAns.md#q186-how-do-you-use-canoe)
* [Q187. What if CAN communication fails?](Embedded-BlogQAns.md#q187-what-if-can-communication-fails)

### AUTOSAR
* [Q188. Explain CAN Driver](Embedded-BlogQAns.md#q188-explain-can-driver)
* [Q189. Explain CANIF](Embedded-BlogQAns.md#q189-explain-canif)
* [Q190. Explain your CANIF work](Embedded-BlogQAns.md#q190-explain-your-canif-work)

## 15. ADC
* [Q191. What is ADC?](Embedded-BlogQAns.md#q191-what-is-adc)
* [Q192. ADC resolution?](Embedded-BlogQAns.md#q192-adc-resolution)
* [Q193. 10-bit vs 12-bit ADC?](Embedded-BlogQAns.md#q193-10-bit-vs-12-bit-adc)
* [Q194. ADC sampling time?](Embedded-BlogQAns.md#q194-adc-sampling-time)
* [Q195. ADC conversion time?](Embedded-BlogQAns.md#q195-adc-conversion-time)
* [Q196. ADC interrupt mode?](Embedded-BlogQAns.md#q196-adc-interrupt-mode)
* [Q197. ADC DMA mode?](Embedded-BlogQAns.md#q197-adc-dma-mode)
* [Q198. ADC calibration?](Embedded-BlogQAns.md#q198-adc-calibration)
* [Q199. How would you validate ADC?](Embedded-BlogQAns.md#q199-how-would-you-validate-adc)

## 16. GPIO
* [Q200. What is GPIO?](Embedded-BlogQAns.md#q200-what-is-gpio)
* [Q201. Input mode?](Embedded-BlogQAns.md#q201-input-mode)
* [Q202. Output mode?](Embedded-BlogQAns.md#q202-output-mode)
* [Q203. Pull-up?](Embedded-BlogQAns.md#q203-pull-up)
* [Q204. Pull-down?](Embedded-BlogQAns.md#q204-pull-down)
* [Q205. Open Drain?](Embedded-BlogQAns.md#q205-open-drain)
* [Q206. Push Pull?](Embedded-BlogQAns.md#q206-push-pull)
* [Q207. GPIO interrupt?](Embedded-BlogQAns.md#q207-gpio-interrupt)
---

## 17. Timers
* [Q208. What is a timer?](Embedded-BlogQAns.md#q208-what-is-a-timer)
* [Q209. Prescaler?](Embedded-BlogQAns.md#q209-prescaler)
* [Q210. Compare mode?](Embedded-BlogQAns.md#q210-compare-mode)
* [Q211. Capture mode?](Embedded-BlogQAns.md#q211-capture-mode)
* [Q212. Timer interrupt?](Embedded-BlogQAns.md#q212-timer-interrupt)
* [Q213. How do you generate periodic interrupts?](Embedded-BlogQAns.md#q213-how-do-you-generate-periodic-interrupts)

## 18. PWM
* [Q214. What is PWM?](Embedded-BlogQAns.md#q214-what-is-pwm)
* [Q215. What is duty cycle?](Embedded-BlogQAns.md#q215-what-is-duty-cycle)
* [Q216. What is PWM frequency?](Embedded-BlogQAns.md#q216-what-is-pwm-frequency)
* [Q217. How is PWM generated?](Embedded-BlogQAns.md#q217-how-is-pwm-generated)
* [Q218. PWM applications?](Embedded-BlogQAns.md#q218-pwm-applications)

## 19. Flash
* [Q219. Explain Flash memory](Embedded-BlogQAns.md#q219-explain-flash-memory)
* [Q220. Why erase before programming?](Embedded-BlogQAns.md#q220-why-erase-before-programming)
* [Q221. What is sector erase?](Embedded-BlogQAns.md#q221-what-is-sector-erase)
* [Q222. What is Flash endurance?](Embedded-BlogQAns.md#q222-what-is-flash-endurance)
* [Q223. What is wear leveling?](Embedded-BlogQAns.md#q223-what-is-wear-leveling)
* [Q224. Flash driver architecture?](Embedded-BlogQAns.md#q224-flash-driver-architecture)
* [Q225. How do you validate Flash writes?](Embedded-BlogQAns.md#q225-how-do-you-validate-flash-writes)

## 20. EEPROM
* [Q226. EEPROM vs Flash?](Embedded-BlogQAns.md#q226-eeprom-vs-flash)
* [Q227. EEPROM endurance?](Embedded-BlogQAns.md#q227-eeprom-endurance)
* [Q228. EEPROM driver design?](Embedded-BlogQAns.md#q228-eeprom-driver-design)

## 21. DMA
* [Q229. What is DMA?](Embedded-BlogQAns.md#q229-what-is-dma)
* [Q230. Why use DMA?](Embedded-BlogQAns.md#q230-why-use-dma)
* [Q231. DMA vs Interrupt?](Embedded-BlogQAns.md#q231-dma-vs-interrupt)
* [Q232. DMA vs Polling?](Embedded-BlogQAns.md#q232-dma-vs-polling)
* [Q233. SPI + DMA?](Embedded-BlogQAns.md#q233-spi--dma)
* [Q234. ADC + DMA?](Embedded-BlogQAns.md#q234-adc--dma)
* [Q235. DMA debugging?](Embedded-BlogQAns.md#q235-dma-debugging)

## 22. Debugging
* [Q236. Explain your debugging methodology](Embedded-BlogQAns.md#q236-explain-your-debugging-methodology)
* [Q237. How do you debug a hang?](Embedded-BlogQAns.md#q237-how-do-you-debug-a-hang)
* [Q238. How do you debug a crash?](Embedded-BlogQAns.md#q238-how-do-you-debug-a-crash)
* [Q239. How do you debug memory corruption?](Embedded-BlogQAns.md#q239-how-do-you-debug-memory-corruption)
* [Q240. How do you debug watchdog reset?](Embedded-BlogQAns.md#q240-how-do-you-debug-watchdog-reset)
* [Q241. How do you debug stack overflow?](Embedded-BlogQAns.md#q241-how-do-you-debug-stack-overflow)
* [Q242. How do you debug function pointer corruption?](Embedded-BlogQAns.md#q242-how-do-you-debug-function-pointer-corruption)

### Debugger Usage
* [Q243. Watch Window?](Embedded-BlogQAns.md#q243-watch-window)
* [Q244. Memory Window?](Embedded-BlogQAns.md#q244-memory-window)
* [Q245. Registers Window?](Embedded-BlogQAns.md#q245-registers-window)
* [Q246. Call Stack?](Embedded-BlogQAns.md#q246-call-stack)
* [Q247. Breakpoints?](Embedded-BlogQAns.md#q247-breakpoints)

## 23. AUTOSAR
* [Q248. Explain AUTOSAR architecture](Embedded-BlogQAns.md#q248-explain-autosar-architecture)
* [Q249. Why AUTOSAR?](Embedded-BlogQAns.md#q249-why-autosar)
* [Q250. Explain Application Layer](Embedded-BlogQAns.md#q250-explain-application-layer)
* [Q251. Explain RTE](Embedded-BlogQAns.md#q251-explain-rte)
* [Q252. Explain BSW](Embedded-BlogQAns.md#q252-explain-bsw)
* [Q253. Explain MCAL](Embedded-BlogQAns.md#q253-explain-mcal)
* [Q254. Explain DIO Driver](Embedded-BlogQAns.md#q254-explain-dio-driver)
* [Q255. Explain CAN Driver](Embedded-BlogQAns.md#q255-explain-can-driver)
* [Q256. Explain SPI Driver](Embedded-BlogQAns.md#q256-explain-spi-driver)
* [Q257. Explain ADC Driver](Embedded-BlogQAns.md#q257-explain-adc-driver)
* [Q258. Explain GPT Driver](Embedded-BlogQAns.md#q258-explain-gpt-driver)

### CDD
* [Q259. What is CDD?](Embedded-BlogQAns.md#q259-what-is-cdd)
* [Q260. Why use CDD?](Embedded-BlogQAns.md#q260-why-use-cdd)
* [Q261. Explain your GDIC/PMIC CDD work](Embedded-BlogQAns.md#q261-explain-your-gdicpmic-cdd-work)

### EB Tresos
* [Q262. What is EB Tresos?](Embedded-BlogQAns.md#q262-what-is-eb-tresos)
* [Q263. What configurations have you done?](Embedded-BlogQAns.md#q263-what-configurations-have-you-done)
---

## 24. Functional Safety
* [Q264. What is ISO26262?](Embedded-BlogQAns.md#q264-what-is-iso26262)
* [Q265. What is Functional Safety?](Embedded-BlogQAns.md#q265-what-is-functional-safety)
* [Q266. What is HARA?](Embedded-BlogQAns.md#q266-what-is-hara)
* [Q267. What is ASIL?](Embedded-BlogQAns.md#q267-what-is-asil)
* [Q268. ASIL A/B/C/D?](Embedded-BlogQAns.md#q268-asil-abcd)
* [Q269. What is a Safety Goal?](Embedded-BlogQAns.md#q269-what-is-a-safety-goal)
* [Q270. What is Traceability?](Embedded-BlogQAns.md#q270-what-is-traceability)
* [Q271. What is FMEA?](Embedded-BlogQAns.md#q271-what-is-fmea)
* [Q272. What is FTA?](Embedded-BlogQAns.md#q272-what-is-fta)

### Your Project
* [Q273. Explain Hyundai Inverter](Embedded-BlogQAns.md#q273-explain-hyundai-inverter)
* [Q274. Explain FUSA Gap Analysis](Embedded-BlogQAns.md#q274-explain-fusa-gap-analysis)
* [Q275. Explain SWAD](Embedded-BlogQAns.md#q275-explain-swad)
* [Q276. Explain SADD](Embedded-BlogQAns.md#q276-explain-sadd)

## 25. MISRA C
* [Q277. What is MISRA C?](Embedded-BlogQAns.md#q277-what-is-misra-c)
* [Q278. Why MISRA?](Embedded-BlogQAns.md#q278-why-misra)
* [Q279. Common MISRA violations?](Embedded-BlogQAns.md#q279-common-misra-violations)
* [Q280. Why avoid dynamic memory?](Embedded-BlogQAns.md#q280-why-avoid-dynamic-memory)
* [Q281. Why avoid unrestricted pointer casting?](Embedded-BlogQAns.md#q281-why-avoid-unrestricted-pointer-casting)
* [Q282. How do you perform static analysis?](Embedded-BlogQAns.md#q282-how-do-you-perform-static-analysis)

## 26. Bootloader
* [Q283. What is a bootloader?](Embedded-BlogQAns.md#q283-what-is-a-bootloader)
* [Q284. Why bootloader?](Embedded-BlogQAns.md#q284-why-bootloader)
* [Q285. Bootloader vs Application?](Embedded-BlogQAns.md#q285-bootloader-vs-application)
* [Q286. Explain firmware update flow](Embedded-BlogQAns.md#q286-explain-firmware-update-flow)
* [Q287. Explain secure firmware update](Embedded-BlogQAns.md#q287-explain-secure-firmware-update)
* [Q288. Have you worked on bootloader integration?](Embedded-BlogQAns.md#q288-have-you-worked-on-bootloader-integration)

## 27. Secure Boot / Cybersecurity
* [Q289. What is Secure Boot?](Embedded-BlogQAns.md#q289-what-is-secure-boot)
* [Q290. What is HSM?](Embedded-BlogQAns.md#q290-what-is-hsm)
* [Q291. What is TrustZone?](Embedded-BlogQAns.md#q291-what-is-trustzone)
* [Q292. What is Firmware Authentication?](Embedded-BlogQAns.md#q292-what-is-firmware-authentication)
* [Q293. What is Secure Firmware Update?](Embedded-BlogQAns.md#q293-what-is-secure-firmware-update)

## 28. Leadership / Staff Engineer
* [Q294. Most difficult bug you solved?](Embedded-BlogQAns.md#q294-most-difficult-bug-you-solved)
* [Q295. Biggest technical challenge?](Embedded-BlogQAns.md#q295-biggest-technical-challenge)
* [Q296. Customer escalation you handled?](Embedded-BlogQAns.md#q296-customer-escalation-you-handled)
* [Q297. How do you mentor engineers?](Embedded-BlogQAns.md#q297-how-do-you-mentor-engineers)
* [Q298. How do you conduct code reviews?](Embedded-BlogQAns.md#q298-how-do-you-conduct-code-reviews)
* [Q299. How do you estimate effort?](Embedded-BlogQAns.md#q299-how-do-you-estimate-effort)
* [Q300. How do you handle technical disagreements?](Embedded-BlogQAns.md#q300-how-do-you-handle-technical-disagreements)
* [Q301. What makes you suitable for Staff Engineer?](Embedded-BlogQAns.md#q301-what-makes-you-suitable-for-staff-engineer)
---
# Final Night-Before Priority (Top 30)

* [Q302. Tell me about yourself](Embedded-BlogQAns.md#q302-tell-me-about-yourself)
* [Q303. LIN Driver](Embedded-BlogQAns.md#q303-lin-driver)
* [Q304. LIN Frame](Embedded-BlogQAns.md#q304-lin-frame)
* [Q305. LIN Checksum](Embedded-BlogQAns.md#q305-lin-checksum)
* [Q306. CAN](Embedded-BlogQAns.md#q306-can)
* [Q307. CAN Arbitration](Embedded-BlogQAns.md#q307-can-arbitration)
* [Q308. CANIF](Embedded-BlogQAns.md#q308-canif)
* [Q309. MCAL](Embedded-BlogQAns.md#q309-mcal)
* [Q310. CDD](Embedded-BlogQAns.md#q310-cdd)
* [Q311. SPI](Embedded-BlogQAns.md#q311-spi)
* [Q312. UART](Embedded-BlogQAns.md#q312-uart)
* [Q313. Interrupt Flow](Embedded-BlogQAns.md#q313-interrupt-flow)
* [Q314. Vector Table](Embedded-BlogQAns.md#q314-vector-table)
* [Q315. ISR](Embedded-BlogQAns.md#q315-isr)
* [Q316. Trap Handler](Embedded-BlogQAns.md#q316-trap-handler)
* [Q317. Missing ISR Entry RCA](Embedded-BlogQAns.md#q317-missing-isr-entry-rca)
* [Q318. volatile](Embedded-BlogQAns.md#q318-volatile)
* [Q319. Function Pointer](Embedded-BlogQAns.md#q319-function-pointer)
* [Q320. Startup Code](Embedded-BlogQAns.md#q320-startup-code)
* [Q321. Linker Script](Embedded-BlogQAns.md#q321-linker-script)
* [Q322. Memory Sections](Embedded-BlogQAns.md#q322-memory-sections)
* [Q323. Device Driver Architecture](Embedded-BlogQAns.md#q323-device-driver-architecture)
* [Q324. TC212 Experience](Embedded-BlogQAns.md#q324-tc212-experience)
* [Q325. Hyundai FUSA Work](Embedded-BlogQAns.md#q325-hyundai-fusa-work)
* [Q326. MISRA C](Embedded-BlogQAns.md#q326-misra-c)
* [Q327. Flash Basics](Embedded-BlogQAns.md#q327-flash-basics)
* [Q328. DMA](Embedded-BlogQAns.md#q328-dma)
* [Q329. Debugging Methodology](Embedded-BlogQAns.md#q329-debugging-methodology)
* [Q330. Why We](Embedded-BlogQAns.md#q330-why-We)
* [Q331. Why You](Embedded-BlogQAns.md#q331-why-you)

---
