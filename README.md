# Projects available at the Embedded Systems Section - DTU

## Hardware acceleration for AI-based noise removal in audio signals

**Description**: 
Voice recognition systems are widespread solutions not only in mobile devices and virtual assistants in smart home environments but also in various industrial settings, where users can give voice commands to complex machinery, resulting in improved operational efficiency and reduced manual interaction. Additional applications of voice recognition also include healthcare assistance systems (for controlling medical devices through voice commands) and devices useful for speech transcription (automatic generation of video subtitles or written transposition of a lecture, in the education sector). However, the quality of the audio signal detected by a microphone is often compromised by the presence of high background noise, especially in industrial environments or particularly crowded places. Through the training of neural networks, it is possible to improve the quality of the audio signal received by a microphone, through appropriate noise filtering.

The goal of the thesis project consists of exploring and implementing hardware for a noise removal system from audio signals, through the use of neural networks. For the hardware implementation, FPGA (Field-Programmable Gate Array) development boards will be used. To this end, it will be necessary to study and implement the part for the acquisition and analog-digital conversion of the audio signal, as well as the preprocessing phase of the audio signal for processing on the FPGA board. It will also be fundamental to implement the neural network for noise removal in hardware. The hardware solution will be evaluated through comparison with solutions implemented in software in terms of audio signal filtering quality and processing speed.

**Supervisors**:
Luca Pezzarossa  (lpez@dtu.dk), 
Riccardo Miccini  (rimi@dtu.dk),
Alessandro Cerioli  (alceri@dtu.dk)

**Keywords/topics**: AI, Hardware accelerators, Digital design.

**Difficulty**: *** (3 stars)

**Type (MSc/BSc/special course)**: 1 student MSc or 2 students BSc

**Language**: English

**Taken or available**: Available

## A specialized toolchain for programming digital microfluidic biochips

**Description**: 
In our research group, we are engaged in the exploration and development of digital microfluidic biochips, focusing on software, firmware, and hardware components. These biochips represent a significant shift from traditional benchtop wet lab processes, offering notable benefits in terms of cost and efficiency. They execute biological and chemical protocols on a miniature scale, possibly revolutionizing the way laboratory tasks are performed.

Building reconfigurable and programmable digital biochips that can be used for a broad range of laboratory protocols inevitably shows the need for an easy and structured process to capture a protocol and translate it into a sequence of steps that can be run on a DMF biochip. This process can be captured with the classical software toolchain consisting of a programming language, a compiler, and an execution platform. This project aims to define a domain-specific language to capture biochemical protocols and to develop the necessary compilation tools for such a language. The language should allow the programmer to define the behavior of the droplets. The compilation tools should implement scheduling and routing techniques (using a combination of known algorithms and possibly new ones) for controlling the droplets' movements and generating low-level commands.

This project is part of a shared effort with other parallel projects to create a stable and usable programming interface and toolchain for digital microfluidics.

**Supervisors**:
Luca Pezzarossa  (lpez@dtu.dk), 
Jan Madsen  (jama@dtu.dk)

**Keywords/topics**: Digital microfluidics, Domain specific languages, WEB-based GUI.

**Difficulty**: ** (2 stars)

**Type (MSc/BSc/special course)**: 2 students BSc

**Language**: English

**Taken or available**: Available
