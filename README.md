# DSP_South_Park_Voice_Changer
## Tagalog Dubbed Video
### Youtube Episode Video Link: https://www.youtube.com/watch?v=GbIk5GXhgUk
### Google Drive Dubbed Video Link: https://bit.ly/3ZHPUaF

![image](https://github.com/TIPKurtMacamay/DSP_South_Park_Voice_Changer/assets/133735418/02d7e729-6f60-477a-a15f-d15a1af18495)

### About South Park:
The animated television series South Park, co-created by Trey Parker and Matt Stone, about four boys living in a dysfunctional Colorado mountain town, has won Emmy and Peabody awards. Kyle, Stan, Cartman, and Kenny manage to have fun despite regional and international tragedies, as well as interference from their parents and famous people. 
### About South Park Episode Deep Learning:
Stan Marsh, a fourth-grader, becomes dependent on the software to write both academic essays and romantic texts to his girlfriend Wendy Testaburger, which puts him in conflict with her, his classmates, and school administrators. The episode parodies the use of the artificial intelligence chatbot ChatGPT, which is acknowledged as a co-writer for the episode.

## Cast of Dubbed Video
* Female A.I (ChatGPT) - John Peter Colin Cumpas
* Wendy Testaburger, Mr. Mackey, and Falconer - Renzo James Cabanos
* Stan Marsh - Kurt Daniel Macamay
* Kyle Broflovski, Eric Cartman, Policeman, Mr. Garrison, and Clyde Donovan - Christian Marc Musni

## How the Voice Changer Works and Adjusting Parameters

This code provides a simple voice changer/alteration tool that can change the pitch of an input audio file. Here's how it works and how you can adjust its parameters:

### How to Use

1. **Input and Output Paths**: Replace the `input_path` and `output_path` variables with the paths to your input voice recording and where you want to save the altered voice respectively. Make sure to specify the file format (e.g., .wav) in the paths.

2. **Loading Audio**: The code uses the `librosa` library to load the audio from the input file. You can specify the sample rate (`sr`) if needed, or use `None` to keep the original sample rate.

3. **Noise Reduction**: The `noisereduce` library is employed to reduce background noise from the input audio. This step helps improve the quality of the altered voice.

4. **Pitch Shifting**: Pitch shifting is performed using `librosa`'s `pitch_shift` function. The `n_steps` parameter controls the amount of pitch shift. By adjusting `n_steps`, you can make the voice sound higher (positive values) or lower (negative values). Experiment with different values to achieve the desired pitch alteration.

5. **Saving the Altered Voice**: The altered voice is saved to the specified `output_path` using the `soundfile` library. Ensure you provide a valid file path and format for saving the altered audio.

6. **Optional: Play the Altered Voice**: The code includes an optional step to play the altered voice using `IPython.display`. You can uncomment this section if you want to listen to the modified audio directly within your Jupyter notebook or Python environment.

### How it Works

This code utilizes a combination of noise reduction and pitch shifting techniques to alter the input voice recording. Here's a brief overview of the process:

1. **Noise Reduction**: Background noise is reduced from the input audio using the `noisereduce` library. This step enhances the clarity of the voice.

2. **Pitch Shifting**: Pitch shifting is applied to the denoised audio using `librosa`'s pitch shifting function. The `n_steps` parameter controls the pitch change. Positive values increase the pitch, while negative values decrease it.

By adjusting the `n_steps` parameter, you can achieve a wide range of voice pitch alterations, allowing for creative audio transformations.

Feel free to experiment with different values for `n_steps` and customize the input and output paths to create unique voice alterations.

For more information on using these libraries, please refer to their respective documentation:

- [librosa Documentation](https://librosa.org/doc/main/index.html)
- [noisereduce Documentation](https://pypi.org/project/noisereduce/)
- [soundfile Documentation](https://pypi.org/project/SoundFile/)

Happy voice altering! 🎤🎶
