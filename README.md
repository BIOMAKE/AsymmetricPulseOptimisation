# AsymmetricPulseOptimisation
Abstract: Transcranial magnetic stimulation (TMS) is a widely-used noninvasive brain stimulation technique based on electromagnetic induction. TMS devices routinely use biphasic magnetic pulses for repetitive TMS neuromodulation protocols and monophasic pulses for low rate probing. However, monophasic pulses with their asymmetric electric field pulse shape offer greater activation selectivity than the more symmetric biphasic pulses, but cannot be generated at rapid rates. A highly efficient asymmetric pulse shape that can be generated at rapid rates would be highly desirable. This paper numerically optimises and searches the waveform space to identify pulse shapes with various asymmetry levels that have minimal energy loss and coil heating. The optimisation results demonstrate asymmetric electric field pulses with near-rectangular electric field and specific current waveform features that lower power consumption. The optimised current waveforms consist of an initial falling phase followed by rapidly rising and falling phases and a trailing slow decay to zero. The initial falling phase has a decay time constant around 275 us---slightly slower than typical axon membrane time constants---and generates a negative starting point for the subsequent main pulse phases, reducing their peak current and hence heating. The optimised waveforms produced up to 80% and 14% less heating than standard monophasic and previously improved monophasic-equivalent pulses.
# Folder Summary
1.  `RecordedOptimisedWaveforms` contains the recorded optimised asymmetric E-field pulses. These waveforms were generated by a modular pulse synthesizer TMS (MPS-TMS) device with six modules.
  * `Opt_` means optimised waveforms.
  * `V-100+1000` means that the negative voltage limit is 100 and the positive voltage limit is 100.
2. `OptimisedWaveforms` contains the optimised asymmetric E-field pulses.
  * `MonophasicPhaseSummary` in both `.xlsx` and `.mat` are files summarising the properties of optimised waveforms.
