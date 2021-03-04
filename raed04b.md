# How does a computer work

**Initially, as a new user, one should be introduced with the machine, which is known as Computer. So, a computer is an electronic device that requires a power supply to work. Power Supply is the lifeline of a computer as water is the lifeline for a human body. A computer machine is used to process the information provided by us. It takes information or data from one end, store it to process, and finally, after completing the processing, it output the result on the other hand. The information it takes at one end is known as Computer Input, and the result that it provides after processing is known as Computer Output. The place where it stores the information is known as Computer Memory or RAM (Random Access Memory). A computer system stores information in bits. Bits is the smallest storage unit of a computer.**

# Major Components of a Computer:

1. **Input**: An input is the information that we provide to the Computer. We provide the information using the Computer's input devices: Keyboard, mouse, microphone, and many more. For example, when we type something using a keyboard, it is known as an Input provided to the Computer.
2. **Storage Space**: It is the place where our input gets stored. It is known as Computer Memory that keeps the data into it. A computer uses a hard drive for storing files and documents. It uses two types of memory, i.e., internal memory and external memory. Internal memory is known as RAM, which is volatile in nature. It stores data temporarily, i.e., when the data is ready to be processed, is loaded into RAM, and after processing, it moves data for the storage. On the other hand, external memory is used to store data permanently until you remove it or it got crashed.
3. **Processing**: The processing of the input is performed by the CPU, which is the Central Processing Unit of the Computer. It is also known as the brain of a computer that is responsible for processing the data provided by the user. The speed of the computer brain is four times faster than the speed of the human brain.
4. **Output**: When we type something using a keyboard, the place where we see the typed input is the Computer Monitor or Computer Screen. A computer screen allows seeing the input we provided to the Computer. Including this, there are different types of output devices of a computer, such as loudspeakers, projectors, printers, and many more.

![computer Componant](https://cdn4.explainthatstuff.com/how-computer-works.png)

# How does it all make a computer to work:

These major components of a computer system together enable a computer to work.

* Operating System**.
* The system's booting process begins that load the operating system (Windows, Linux, Mac, etc.) with all associated files. The bootstrap loader starts the booting of the system. So, in this way, Windows and its other essential services get loaded to the system.
* As the operating system has been loaded to the Computer, the installed Hardware of the systems becomes active and able to communicate with the CPU. The communication of the hardware devices is performed via an interrupt request (IRQ). When the current task is already in execution, the interrupt controller sends the request to CPU to stop processing a new hardware request until the execution of the current task gets completed. The CPU keeps the new request on hold, and that process is stored as a memory address in the memory stack. When the current task execution is finished, the task on hold is resumed and processed.
However, if the Computer fails in the POST test, an irregular POST is encountered. We can understand the irregular POST when we hear a beep coming from the system that notifies us that some problem has occurred.
* When we switch on the computer system by pressing the power button, a signal reaches the power supply that converts the alternate current into the direct current, also known as DC. After that, a proper ample power is supplied to each component of the Computer.
* With no issues, all components come in their active state, the power supply sends a signal to the motherboard and CPU via transistors. During the time, the processor removes the leftover data in the memory, and the CPU becomes ready to take over the instruction (input) and process it.
* A POST (power-on self-test) is performed on the Computer in a sequence to ensure that the major computer components exist and work properly. When the Computer passes the test, firstly, the 64-bytes memory wakes because it carries the system time and date information and all other hardware-related information installed on the system. This information starts loading and POST checks and compares this information with the system settings. If compared successfully, it loads the basic drivers (that allows communication of hardware devices with CPU and Computer to continue to boot) and interrupts handlers for the installed Hardware such as a keyboard, hard drive, mouse, and many more.
* After that, POST checks the display adapter, and with no issues found, it loads the display that we see on the computer monitor. Next, it is checked that whether Cold boot or reboot (warm boot) is performed by looking at the memory address 0000:0472. If it is 1234h, it means it is a reboot, and the rest of the POST steps are skipped. But, if it not so, it means it is a cold boot, and the remaining POST steps are continued.
* Now, the RAM installed on the computer system is checked.

## Binary and Data

All computer data is represented using binary, a number system that uses 0s and 1s. Binary digits can be grouped together into bytes. There are two popular methods for converting binary to denary.

Computers use binary - the digits 0 and 1 - to store data. A binary digit, or bit, is the smallest unit of data in computing. It is represented by a 0 or a 1. Binary numbers are made up of binary digits (bits), eg the binary number 1001.

The circuits in a computer's processor are made up of billions of transistors. A transistor is a tiny switch that is activated by the electronic signals it receives. The digits 1 and 0 used in binary reflect the on and off states of a transistor.

Computer programs are sets of instructions. Each instruction is translated into machine code - simple binary codes that activate the CPU. Programmers write computer code and this is converted by a translator into binary instructions that the processor can execute.

All software, music, documents, and any other information that is processed by a computer, is also stored using binary.

## Circuits

A circuit is the path that an electric current travels on, and a simple circuit contains three components necessary to have a functioning electric circuit, namely, a source of voltage, a conductive path, and a resistor.

Circuits are driven by flows. Flows are ubiquitous in nature and are often the result of spatial differences in potential energy. Water flows downriver due to changes in height, tornadoes swirl due to gentle temperature gradients, and sucrose flows from the leaves of trees to their distal parts due to differences in water potential. Even life itself is due to a clever hack by which living organisms serve as a conduit for the flow of solar energy. Perhaps then it is no surprise that electronic devices (certainly the one you're reading this on now) are driven by flows.

![simple ciruit](https://circuitfever.com/wp-content/uploads/2019/11/OR-Gate-Using-Diodes.png)
