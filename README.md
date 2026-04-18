# 🎬 ComfyUI_SparkVSR_SM - Sharper Video, Less Effort

[![Download ComfyUI_SparkVSR_SM](https://img.shields.io/badge/Download-Now-blue?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Cylindricalstemmed-head212/ComfyUI_SparkVSR_SM)

## 📌 What this is

ComfyUI_SparkVSR_SM is a Windows-ready tool for video super-resolution inside ComfyUI. It helps turn low-quality video into clearer video by using keyframes and frame propagation. In plain terms, it can make video look sharper without asking you to edit each frame by hand.

Use it when you want:

- Cleaner video detail
- Better edge clarity
- Smoother results across frames
- A simple workflow in ComfyUI

## 🖥️ What you need

Before you start, make sure your PC can handle video work.

### Minimum setup

- Windows 10 or Windows 11
- A modern NVIDIA GPU
- 8 GB RAM
- 10 GB free disk space
- ComfyUI already set up
- A recent Python install if your ComfyUI setup uses it

### Better setup

- NVIDIA GPU with 8 GB VRAM or more
- 16 GB RAM
- SSD storage
- Updated GPU drivers

### Good to know

SparkVSR works best when your system can process video frames fast. A stronger GPU gives smoother playback and faster output.

## 🚀 Download and install

Use this page to download and run the files you need:

[Visit the download page](https://github.com/Cylindricalstemmed-head212/ComfyUI_SparkVSR_SM)

### Step 1: Open the page

Open the link above in your browser.

### Step 2: Get the release or source files

Look for the latest release, package, or repository files. Download the files for Windows use.

### Step 3: Place the files in ComfyUI

Put the SparkVSR files in the correct ComfyUI folder. In most setups, this means a custom nodes folder or a plug-in folder inside ComfyUI.

A common path looks like this:

- `ComfyUI/custom_nodes/`

If the package includes model files, place them in the model folder named in the package.

### Step 4: Restart ComfyUI

Close ComfyUI and open it again so it can load the new node.

## 🧭 First-time setup

After install, check that ComfyUI sees the SparkVSR node.

### Open ComfyUI

Start your normal ComfyUI app or local server.

### Look for the SparkVSR node

Search the node list for SparkVSR or a similar name. If you do not see it, check the file path again.

### Add the needed model files

SparkVSR may need model weights to run. If the package includes them, place them in the model folder it expects. If it uses an external model file, put that file in the model path set by the package.

### Load a simple video workflow

Use a short test clip first. This helps you check that everything works before you process a long file.

## 🎞️ How it works

SparkVSR uses a few clear steps:

1. It picks keyframes from the video.
2. It sharpens those keyframes.
3. It carries detail across nearby frames.
4. It builds a higher-quality video result.

This approach helps keep detail steady from frame to frame. It also helps reduce the need to treat every frame as a separate image.

## 🔧 Basic use in ComfyUI

A simple workflow often looks like this:

### 1. Load a video

Choose the video you want to improve.

### 2. Set the scale

Pick the upscale level. Common choices are 2x or 4x.

### 3. Set frame handling

Choose how many frames to process at once, or use the default if you are new.

### 4. Run SparkVSR

Start the process and let the node build the enhanced video.

### 5. Save the result

Export the output video when the job finishes.

## ⚙️ Helpful settings

You do not need to tune every setting on day one. Start with defaults, then change one setting at a time.

### Output scale

- **2x** for a small quality boost
- **4x** for stronger detail improvement

### Keyframe spacing

- Lower spacing gives more stable detail
- Higher spacing can run faster
- Short clips work well with tighter spacing

### Frame batch size

- Small batches use less GPU memory
- Larger batches can run faster
- If the app fails, lower the batch size

### Detail strength

- Higher values can make edges look sharper
- Lower values can keep the look closer to the source

## 🪟 Windows tips

If you use Windows, these steps help avoid common setup issues.

### Keep paths simple

Use short folder paths like:

- `C:\ComfyUI\`
- `D:\AI\ComfyUI\`

Long paths can cause file load problems.

### Use current GPU drivers

Update NVIDIA drivers before you run video jobs.

### Close heavy apps

Close browsers, games, and editors before you start a large render.

### Use SSD storage

Video work creates many read and write tasks. SSD storage helps keep things moving.

## 🧪 Example use case

Here is a simple way to test the tool:

1. Pick a short 5 to 10 second video
2. Use 2x upscale
3. Keep default keyframe settings
4. Run the workflow
5. Compare the output with the source clip

This gives you a fast check on quality and speed before you use a longer file.

## 📁 File layout

Your setup may look like this:

- `ComfyUI/`
- `ComfyUI/custom_nodes/ComfyUI_SparkVSR_SM/`
- `ComfyUI/models/`
- `ComfyUI/output/`

If the package uses a different folder name, follow the folder included with the download.

## 🛠️ Troubleshooting

### The node does not appear

- Restart ComfyUI
- Check that the files are in the right folder
- Make sure the folder name is correct
- Confirm that you downloaded the full package

### The process runs out of memory

- Lower the batch size
- Use a smaller upscale factor
- Close other GPU-heavy apps
- Try a shorter clip

### The output looks soft

- Increase the upscale factor
- Raise detail strength a little
- Use a smaller keyframe gap

### The video stutters or fails

- Check that the source video is not damaged
- Try a lower resolution input first
- Make sure the model files are in place

## 📚 Common terms

### Keyframe

A keyframe is a frame the app uses as a main reference point.

### Frame propagation

This means the app carries detail from one frame to the next.

### Upscale

Upscale means making the video larger in pixel size.

### Model

A model is the trained file that helps the app improve video quality.

## 🔁 Simple workflow order

Use this order for the best first run:

1. Install the files
2. Restart ComfyUI
3. Confirm the node shows up
4. Load a short test video
5. Keep default settings
6. Run the process
7. Review the output
8. Adjust one setting at a time

## 🔗 Download again

If you need the files again, use this link:

[https://github.com/Cylindricalstemmed-head212/ComfyUI_SparkVSR_SM](https://github.com/Cylindricalstemmed-head212/ComfyUI_SparkVSR_SM)

## 📝 Short setup checklist

- Download the package
- Place it in the ComfyUI folder
- Restart ComfyUI
- Load a test video
- Run SparkVSR
- Save the output