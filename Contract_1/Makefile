CC = solc
SOURCE = Contract_1

$(SOURCE): $(SOURCE).sol
	$(CC) -o Target --bin --abi $(SOURCE).sol

git:

	git commit -a
	git push
deploy:
	@echo "Deploy on Etehereum..."

clean:
	rm -f ./Target/*.bin
	rm -f ./Target/*.abi
