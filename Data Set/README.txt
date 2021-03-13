
——————————————————————————————————————————————————————————————————————————————
	The Voice Conversion Challenge 2018: database and results
——————————————————————————————————————————————————————————————————————————————

Authors:
Jaime Lorenzo-Trueba(1), Junichi Yamagishi(1)(2), Tomoki Toda(3) 
Daisuke Saito(4), Fernando Villavicencio(5), Tomi Kinnunen(6), Zhenhua Ling(7)

Affiliations:
(1)National Institute of Informatics, Japan
(2)The Centre for Speech Technology Research, The University of Edinburgh, UK
(3)Information Technology Center, Nagoya University, Japan
(4)The University of Tokyo, Japan
(5)ObEN, USA
(6)University of Eastern Finland, Finland
(7)University of Science and Technology of China, China

——————————————————————————————————————————————————————————————————————————————
Introduction: 

Voice conversion (VC) is a technique to transform a speaker identity included in a source speech waveform into a different one while preserving linguistic information of the source speech waveform. 

In 2016, we have launched the Voice Conversion Challenge (VCC) 2016 [1][2] at Interspeech 2016. The objective of the 2016 challenge was to better understand different VC techniques built on a freely-available common dataset to look at a common goal, and to share views about unsolved problems and challenges faced by the current VC techniques. The VCC 2016 focused on the most basic VC task, that is, the construction of VC models that automatically transform the voice identity of a source speaker into that of a target speaker using a parallel clean training database where source and target speakers read out the same set of utterances in a professional recording studio. 17 research groups had participated in the 2016 challenge. The challenge was successful and it established new standard evaluation methodology and protocols for bench-marking the performance of VC systems. 

In 2018, we launched the second edition of VCC, the VCC 2018. In this second edition, we have revised three aspects of the challenge. First, we have reduced the amount of speech data used for the construction of participant's VC systems to half. This is based on feedback from participants in the previous challenge and this is also essential for practical applications. Second, we introduced a more challenging task refereed to a Spoke task in addition to a similar task to the 1st edition, which we call a Hub task. In the Spoke task, participants need to build their VC systems using a non-parallel database in which source and target speakers read out different sets of utterances. We then evaluate both parallel and non-parallel voice conversion systems via the same large-scale crowdsourcing listening test. Third, we also attempted to bridge the gap between the ASV and VC communities. Since new VC systems developed for the VCC 2018 may be strong candidates for enhancing the ASVspoof 2015 database, we also asses spoofing performance of the VC systems based on anti-spoofing scores. 

This repository contains the training and evaluation data released to participants, submissions from participants, and the listening test results for the 2018 Voice Conversion Challenge. For more details about the challenge and the listening test results please refer to [3].

[1] Tomoki Toda, Ling-Hui Chen, Daisuke Saito,Fernando Villavicencio, Mirjam Wester, Zhizheng Wu, Junichi Yamagishi "The Voice Conversion Challenge 2016"  in Proc. of Interspeech, San Francisco. 

[2] Mirjam Wester, Zhizheng Wu, Junichi Yamagishi "Analysis of the Voice Conversion Challenge 2016 Evaluation Results" in Proc. of Interspeech 2016.

[3] Jaime Lorenzo-Trueba, Junichi Yamagishi, Tomoki Toda, Daisuke Saito, Fernando Villavicencio, Tomi Kinnunen, Zhenhua Ling, "The Voice Conversion Challenge 2018: Promoting Development of Parallel and Nonparallel Methods", Proc Speaker Odyssey 2018, June 2018. 

If you publish using any of the data in this dataset please reference the above three papers. 


——————————————————————————————————————————————————————————————————————————————
Data structure:

Training and evaluation data 
vcc2018_database_training: training data for building parallel and non-parallel VC systems released to participants during the challenge
vcc2018_database_evaluation: evaluation data (source speaker's data) released to participants during the challenge 
vcc2018_database_reference: evaluation data (target speaker's data) used as reference in listening tests 
vcc2018_database_evaluation_transcriptions: transcriptions of evaluation data. This was NOT released to participants during the challenge 

submissions from participants
vcc2018_submitted_systems_converted_speech: converted speech of submitted systems 
vcc2018_submitted_systems_system_descriptions: descriptions of submitted systems provided by participants

listening test results
vcc2018_evaluation_results: listening test results 
vcc2018_evaluation_listening_test_raw_results: raw results of listening tests 
vcc2018_evaluation_listeners_information: information of listeners who participated in the listening tests


——————————————————————————————————————————————————————————————————————————————
COPYING: 
You are free to use this database under Creative Commons Attribution License (CC-BY). 

Regarding Creative Commons License: Attribution 4.0 International (CC BY 4.0), 
please see https://creativecommons.org/licenses/by/4.0/

THIS DATABASE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND 
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED 
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. 
IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, 
INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, 
BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, 
OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, 
WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) 
ARISING IN ANY WAY OUT OF THE USE OF THIS DATABASE, EVEN IF ADVISED OF THE 
POSSIBILITY OF SUCH DAMAGE.

——————————————————————————————————————————————————————————————————————————————
ACKNOWLEDGEMENTS:
We are grateful to iFlytek Ltd. for sponsoring the evaluation of the VCC 2018. This work was partially supported by MEXT KAKENHI Grant Numbers (15H01686, 16H06302, 17H04687, 17H06101)

The VCC 2018 database is based on the DAPS corpus below:  
Gautham J. Mysore, DAPS (Device and Produced Speech) Dataset - A dataset of professional production quality speech and corresponding aligned speech recorded on common consumer device, https://archive.org/details/daps_dataset 



