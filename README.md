import tim

def countdown(seconds):
    while seconds > 0:
        print(f"Time left: {seconds} seconds")
        time.sleep(1)
        seconds -= 1
    print("⏰ Time’s up!")

if __name__ == "__main__":
    countdown(5)
