# Python
Exercise_python
### Fastq to fasta
 读取fastq文件，第1行的header作为fasta的header;
 读取fastq文件，第2行的seq作为fasta格式的seq; 
 格式化输出fasta文件


#### read_fasta
读取fasta文件，让最终每个fasta文件都能 返回header和seq
分析:
 当有>的时候，就为标题行;
 当不是>的时候，就是序列信息;
 当是序列信息的时候，需要进行序列的拼接;
 最终返回序列的header与seq



 
