# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.605 ops/ms
# Warmup Iteration   2: 5.616 ops/ms
# Warmup Iteration   3: 9.155 ops/ms
Iteration   1: 9.367 ops/ms
Iteration   2: 9.914 ops/ms
Iteration   3: 9.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.690 ±(99.9%) 5.237 ops/ms [Average]
  (min, avg, max) = (9.367, 9.690, 9.914), stdev = 0.287
  CI (99.9%): [4.453, 14.927] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.800 ops/ms
# Warmup Iteration   2: 9.889 ops/ms
# Warmup Iteration   3: 9.597 ops/ms
Iteration   1: 10.335 ops/ms
Iteration   2: 10.547 ops/ms
Iteration   3: 10.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.471 ±(99.9%) 2.156 ops/ms [Average]
  (min, avg, max) = (10.335, 10.471, 10.547), stdev = 0.118
  CI (99.9%): [8.315, 12.628] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.856 ops/ms
# Warmup Iteration   2: 9.460 ops/ms
# Warmup Iteration   3: 9.569 ops/ms
Iteration   1: 9.855 ops/ms
Iteration   2: 10.126 ops/ms
Iteration   3: 10.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.073 ±(99.9%) 3.573 ops/ms [Average]
  (min, avg, max) = (9.855, 10.073, 10.236), stdev = 0.196
  CI (99.9%): [6.500, 13.645] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.399 ops/ms
# Warmup Iteration   2: 7.627 ops/ms
# Warmup Iteration   3: 8.328 ops/ms
Iteration   1: 8.738 ops/ms
Iteration   2: 8.652 ops/ms
Iteration   3: 8.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.660 ±(99.9%) 1.344 ops/ms [Average]
  (min, avg, max) = (8.591, 8.660, 8.738), stdev = 0.074
  CI (99.9%): [7.317, 10.004] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.585 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.443 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.003 ms/op
Iteration   1: 3.308 ±(99.9%) 0.007 ms/op
Iteration   2: 3.090 ±(99.9%) 0.005 ms/op
Iteration   3: 3.126 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.175 ±(99.9%) 2.128 ms/op [Average]
  (min, avg, max) = (3.090, 3.175, 3.308), stdev = 0.117
  CI (99.9%): [1.047, 5.302] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.843 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.311 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.003 ms/op
Iteration   1: 3.021 ±(99.9%) 0.006 ms/op
Iteration   2: 3.120 ±(99.9%) 0.009 ms/op
Iteration   3: 3.155 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.099 ±(99.9%) 1.267 ms/op [Average]
  (min, avg, max) = (3.021, 3.099, 3.155), stdev = 0.069
  CI (99.9%): [1.832, 4.366] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.945 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.458 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.001 ms/op
Iteration   1: 3.139 ±(99.9%) 0.001 ms/op
Iteration   2: 3.247 ±(99.9%) 0.002 ms/op
Iteration   3: 3.204 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.196 ±(99.9%) 0.994 ms/op [Average]
  (min, avg, max) = (3.139, 3.196, 3.247), stdev = 0.054
  CI (99.9%): [2.203, 4.190] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.453 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.005 ms/op
Iteration   1: 3.761 ±(99.9%) 0.007 ms/op
Iteration   2: 3.663 ±(99.9%) 0.008 ms/op
Iteration   3: 3.698 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.708 ±(99.9%) 0.909 ms/op [Average]
  (min, avg, max) = (3.663, 3.708, 3.761), stdev = 0.050
  CI (99.9%): [2.799, 4.616] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.512 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.008 ms/op
Iteration   1: 3.149 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  18.186 ms/op
                 createUser·p0.9999: 20.011 ms/op
                 createUser·p1.00:   20.939 ms/op

Iteration   2: 3.221 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  12.683 ms/op
                 createUser·p0.9999: 23.731 ms/op
                 createUser·p1.00:   25.133 ms/op

Iteration   3: 3.154 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.421 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  11.538 ms/op
                 createUser·p0.9999: 17.882 ms/op
                 createUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302442
  mean =      3.174 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20698 
    [ 2.500,  5.000) = 275796 
    [ 5.000,  7.500) = 5181 
    [ 7.500, 10.000) = 373 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 165 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     14.249 ms/op
     p(99.9900) =     21.712 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.303 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.008 ms/op
Iteration   1: 3.236 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.352 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  13.042 ms/op
                 existUser·p0.9999: 22.060 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 3.106 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  15.139 ms/op
                 existUser·p0.9999: 22.403 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   3: 3.257 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.646 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  12.429 ms/op
                 existUser·p0.9999: 21.999 ms/op
                 existUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300145
  mean =      3.198 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22303 
    [ 2.500,  5.000) = 271521 
    [ 5.000,  7.500) = 5406 
    [ 7.500, 10.000) = 450 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     22.117 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.232 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.011 ms/op
Iteration   1: 3.163 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  13.229 ms/op
                 getUser·p0.9999: 20.378 ms/op
                 getUser·p1.00:   20.972 ms/op

Iteration   2: 3.300 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.818 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  9.761 ms/op
                 getUser·p0.9999: 22.925 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   3: 3.140 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  11.278 ms/op
                 getUser·p0.9999: 21.627 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299873
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14242 
    [ 2.500,  5.000) = 278612 
    [ 5.000,  7.500) = 6453 
    [ 7.500, 10.000) = 226 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     12.565 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     23.298 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.257 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.810 ±(99.9%) 0.011 ms/op
Iteration   1: 3.843 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   7.779 ms/op
                 listUser·p0.999:  16.362 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   2: 3.714 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.743 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  14.416 ms/op
                 listUser·p0.9999: 19.562 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   3: 3.721 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.271 ms/op
                 listUser·p0.9999: 14.991 ms/op
                 listUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255408
  mean =      3.759 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 93 
    [ 2.500,  5.000) = 245799 
    [ 5.000,  7.500) = 7394 
    [ 7.500, 10.000) = 1317 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 422 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.477 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     20.852 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.690 ± 5.237  ops/ms
ClientPb.existUser                       thrpt       3  10.471 ± 2.156  ops/ms
ClientPb.getUser                         thrpt       3  10.073 ± 3.573  ops/ms
ClientPb.listUser                        thrpt       3   8.660 ± 1.344  ops/ms
ClientPb.createUser                       avgt       3   3.175 ± 2.128   ms/op
ClientPb.existUser                        avgt       3   3.099 ± 1.267   ms/op
ClientPb.getUser                          avgt       3   3.196 ± 0.994   ms/op
ClientPb.listUser                         avgt       3   3.708 ± 0.909   ms/op
ClientPb.createUser                     sample  302442   3.174 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.421           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.498           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.249           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.712           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.133           ms/op
ClientPb.existUser                      sample  300145   3.198 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.646           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.877           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.117           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.298           ms/op
ClientPb.getUser                        sample  299873   3.200 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.051           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.104           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.546           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.565           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.151           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.216           ms/op
ClientPb.listUser                       sample  255408   3.759 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.192           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.129           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.477           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.209           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.713           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.562           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.939           ms/op
