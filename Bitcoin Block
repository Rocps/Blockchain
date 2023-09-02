# Block

# Block number
BLOCK_NUMBER = 0

# Block size 1MB
BLOCK_SIZE = 80

# Block header
BLOCK_HEADER = {
    "version": 0x00000000,
    "previous_block": "0000000000000000000000000000000000000000000000000000000000000000",
    "merkle_root_hash": "4a5e1e4baab89f3a32518a88c31bc87f618f76673e2cc77ab2127b7afdeda33b",
    "timestamp": 1231000000,  # 2009-01-31 18:15:00 UTC
    "difficulty_target": 0x1d00ffff,
    "nonce": 123456,
}

# Block body
BLOCK_BODY = {
    "transaction_counter": 1,
    "transactions": [
        {
            "from": "12345678901234567890123456789012",
            "to": "98765432109876543210987654321098",
            "amount": 1,
        },
    ],
}

# Block hash
BLOCK_HASH = calculate_block_hash(BLOCK_HEADER, BLOCK_BODY)
# 22e518e8300769b60d0117331a45b2300847e630c709343253a8e90999c66952

# Next block
NEXT_BLOCK_NUMBER = 1

///

# Structure of a block in a blockchain

# A block is a collection of data that is stored in a blockchain.
# A block consists of a header and a body.

# The header contains information about the block, such as the block number, the previous block hash, the merkle root hash, the timestamp, the difficulty target, and the nonce.

# The body contains the data for the block, such as the transaction counter and the transactions.

# The block hash is a value that is calculated from the header and the body of the block.
# The block hash is used to verify the authenticity of the block and to ensure that it cannot be modified.

# The next block number is the number of the block that will be added next to the current block.
