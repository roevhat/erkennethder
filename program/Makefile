FILE=program.ino
TARGET=arduino:avr:uno
#TARGET=arduino:sam:arduino_due_x_dbg
ARDUINO_PATH=/home/roevhat/tools/arduino-1.5/arduino
PORT=/dev/ttyACM0

verify:
	@$(ARDUINO_PATH) $(FILE) --verify --board $(TARGET) --port $(PORT)

upload:
	@$(ARDUINO_PATH) $(FILE) --upload --board $(TARGET) --port $(PORT)

serial:
	picocom $(PORT)