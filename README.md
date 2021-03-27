# Clone Factory

# How to deploy with truffle ? <br>
1. Deploy files .sol in ./libraries
2. Link CloneERC20 with SafeMath
3. Deploy CloneERC20
4. Link ClonePair with Math, UQ112x112 and CloneERC20
5. Deploy ClonePair
6. Link CloneFactory with ClonePair
7. Deploy CloneFactory with parameter address

# Local Development

The following assumes the use of `node@>=10`.

## Install Dependencies

`yarn`

## Compile Contracts

`yarn compile`

## Run Tests

`yarn test`
"# clone-swap-core" 
