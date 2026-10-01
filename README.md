# Casmi26
# Commend to join the chunk files
git clone https://github.com/SS-Pradeep/Casmi26.git
cd Casmi26
cat chunks/train_part_* > train.parquet
sha256sum -c chunks/train.sha256
