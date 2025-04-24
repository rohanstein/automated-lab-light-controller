# Automated Lab Light Controller

A Raspberry Pi-based robotic system designed to automate the manual operation of an old laboratory light source used in bacterial culture experiments. This setup was built to regulate light/dark exposure cycles for photosynthetic bacteria, where manual operation was impractical and inconsistent.

## 🧪 Background

In my Ph.D. research, I work with bacteria that require controlled light exposure. The lab equipment available to me was not programmable and had to be manually switched on/off. To maintain consistent experimental conditions—especially overnight—I built a DIY solution using available hardware, Python, and a Raspberry Pi.

## ⚙️ What It Does

- Operates a lab light source mechanically via a custom-built actuator (using salvaged hardware).
- Connected to a Raspberry Pi that controls the actuator based on a set light/dark schedule.
- Receives simple command messages from my phone, allowing remote manual overrides when needed.

## 🧰 Tools & Technologies

- **Raspberry Pi 3B+**
- **Python** (for scripting control logic and communication)
- **GPIO control** for hardware interfacing
- **Messaging/Trigger System**: Telegram messaging app trigger to send commands
- **Scrap parts from dismantled automations** The actuator was put together using scrap parts, zip-ties, etc. lying around with me from a dismantled rig. 

## 📸 Images
Final set up: https://github.com/rohanstein/automated-lab-light-controller/blob/main/actuator_setup.jpg?raw=true

Actuator controlling light exposure to bacterial samples: https://github.com/rohanstein/automated-lab-light-controller/blob/main/actuator_controlling_light%20exposure.jpg?raw=true

## 💡 What I Learned

- Practical hardware automation with Raspberry Pi and GPIO.
- Writing efficient and resilient Python scripts for real-time control.
- Troubleshooting timing issues, connectivity, and physical hardware quirks.
- How small DIY projects can improve lab efficiency in a big way.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 🙋‍♂️ Contact

If you’re curious or would like to collaborate on lab automation, feel free to reach out!

---

