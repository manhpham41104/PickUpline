# PickUpline
import random

def generate_pickup_line():
    lines = [
        "Are you a magician? Because whenever I look at you, everyone else disappears.",
        "Do you have a map? I keep getting lost in your eyes.",
        "Are you a Wi-Fi signal? Because I'm feeling a connection.",
        "Are you a camera? Every time I see you, I smile.",
        "If you were a vegetable, you'd be a cute-cumber!",
        "Is your name Google? Because you've got everything I've been searching for.",
    ]
    return random.choice(lines)

if __name__ == "__main__":
    print(generate_pickup_line())
