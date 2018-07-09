CC = solc
SOURCE = Contract_1

#all: appname

$(SOURCE): $(SOURCE).sol
	$(CC) -o Target --bin --abi $(SOURCE).sol

deploy:
	@echo "Deploy on Etehereum..."

clean:
	rm -f ./Target/*.bin
	rm -f ./Target/*.abi
