INSTRUMENTS / GENERATORS

# 3x Osc

**3x Osc**  is a deceptively powerful 3 x Oscillator, subtractive synthesizer feeding the FL Studio  [Sampler](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/chansettings_sampler.htm). It has been used in 1,000,000s of FL Studio projects since 2000 and continues to bring bright sunny days to synthesists world wide.

To reduce CPU load the oscillators are anti-aliased during rendering only. This means the rendered tracks may sound better, but rendering will be slower.

See a 3 OSC  ![](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/img_glob/global_video.gif)  [Demo Video here](https://www.youtube.com/watch?v=eFB8DUnk8fA)  and check the 3x Osc preset forum  [here](https://support.image-line.com/redirect/3OSCForum).

![](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/img_plug/3xOsc.png)

**NOTE:**  3x Osc is an old-school synth with a raw (aliased) sound from the 90's.

## Video Demos

This project uses ONLY 3x OSC ...

## Parameters

### OSC 1, 2, 3 Parameters

This section covers parameters for all of the oscillators.

-   **Shape Selectors**  - Buttons in each of the oscillators, allowing one of the following choices: sine, triangle, square, saw, rounded saw, noise, custom. Custom uses whatever sample is loaded in the channel  [Sampler Settings](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/chansettings_sampler.htm)  page.
-   **Invert Switch**  - Allows you to invert the phase of the oscillator. When you mix two oscillators with equal settings, and one of them is inverted, they cancel each other and no sound is produced. However, if you set the Fine frequency to a slightly different value, this can produce interesting flanging/phasing effects.
-   **Phase OFS**  - Allows you to set different phase offset for the left and right channels of the generator. The offset results in the oscillator starting at a different point on the oscillator's shape (for example, start at the highest value of the sine function instead at the zero point). Stereo phase offset adds to the richness and stereo panorama of the sound produced.
-   **Detune**  - Allows you to de-tune the stereo sound of the generator, by applying a slightly different frequency at the left and right sound channels. This adds to the stereo panorama of the sound produced, and creates a 'stereo flange' effect. When the knob is in the middle, the effect is turned off.
-   **Coarse Tuning**  - Sets the coarse tuning (range -24 to +24 semitones) of the individual oscillators.
-   **Fine Tuning**  - Sets the fine tuning (range -1 to +1 semitone) of the individual oscillators.
-   **Panning**  - Sets the stereo panning of the individual oscillators.
-   **Level**  - Sets the relative volume of each of the oscillators. Relative, here, means the overall sound output is kept at the same level, but the relative amount of each of the oscillators is adjustable. Oscillator 1 does not have a Level control. For example, to mix 50% of oscillator 1 and 2, set the volume of oscillator 2 to 50%. To mix all 3 oscillators at 33.33..%, set the volume knobs to 50% for oscillators 2 and 3. To mix only oscillator 1 at 100%, set all other volume levels to zero.

### Other Parameters

-   **AM OSC 3**  (OSC 3 Amplitude Modulation) - Switch on to use Oscillator 3 as an amplitude modulator of oscillators 1 and 2.
-   **HQ**  - High quality anti-aliased oscillators providing virtually alias free from 15 Hz to 20 kHz.  **NOTE:**  Legacy projects will load with this OFF by default.
-   **Phase Rand**  - Adds 'randomness' to the stereo phase of all oscillators. Low values can make the sound slightly more natural, while higher values can be used as a special effect.

## Notes & Tips

-   **Presets**  - Since the 3xOsc generator acts as an addition to the standard integrated  [Sampler](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/chansettings_sampler.htm), it is usually not enough to save direct 3xOsc presets rather than full Channel presets which hold the complete sound. As a result, default 3x Osc presets will be found in  **/Channel presets/3x Osc/**  in the Browser.
-   **Stereo Phasing**  can introduce clicks when the oscillators start somewhere inside the waveform other than zero level. You can fix this by using a V**olume Envelope**  with a short attack time.

----------

**Plugin Credits:** Didier Dambrin
