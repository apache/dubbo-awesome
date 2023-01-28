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
# Warmup Iteration   1: 2.428 ops/ms
# Warmup Iteration   2: 5.708 ops/ms
# Warmup Iteration   3: 9.039 ops/ms
Iteration   1: 9.879 ops/ms
Iteration   2: 10.079 ops/ms
Iteration   3: 9.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.833 ±(99.9%) 4.978 ops/ms [Average]
  (min, avg, max) = (9.539, 9.833, 10.079), stdev = 0.273
  CI (99.9%): [4.855, 14.810] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.615 ops/ms
# Warmup Iteration   2: 9.466 ops/ms
# Warmup Iteration   3: 9.861 ops/ms
Iteration   1: 9.854 ops/ms
Iteration   2: 10.076 ops/ms
Iteration   3: 10.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.103 ±(99.9%) 4.829 ops/ms [Average]
  (min, avg, max) = (9.854, 10.103, 10.381), stdev = 0.265
  CI (99.9%): [5.275, 14.932] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.176 ops/ms
# Warmup Iteration   2: 8.154 ops/ms
# Warmup Iteration   3: 9.556 ops/ms
Iteration   1: 10.222 ops/ms
Iteration   2: 9.970 ops/ms
Iteration   3: 10.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.147 ±(99.9%) 2.809 ops/ms [Average]
  (min, avg, max) = (9.970, 10.147, 10.250), stdev = 0.154
  CI (99.9%): [7.338, 12.956] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.182 ops/ms
# Warmup Iteration   2: 7.808 ops/ms
# Warmup Iteration   3: 8.165 ops/ms
Iteration   1: 8.102 ops/ms
Iteration   2: 8.516 ops/ms
Iteration   3: 8.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.424 ±(99.9%) 5.227 ops/ms [Average]
  (min, avg, max) = (8.102, 8.424, 8.652), stdev = 0.287
  CI (99.9%): [3.196, 13.651] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.673 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.006 ms/op
Iteration   1: 3.320 ±(99.9%) 0.003 ms/op
Iteration   2: 3.132 ±(99.9%) 0.005 ms/op
Iteration   3: 3.086 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.180 ±(99.9%) 2.263 ms/op [Average]
  (min, avg, max) = (3.086, 3.180, 3.320), stdev = 0.124
  CI (99.9%): [0.917, 5.442] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.325 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.430 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.004 ms/op
Iteration   1: 3.040 ±(99.9%) 0.004 ms/op
Iteration   2: 3.144 ±(99.9%) 0.002 ms/op
Iteration   3: 2.949 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.044 ±(99.9%) 1.777 ms/op [Average]
  (min, avg, max) = (2.949, 3.044, 3.144), stdev = 0.097
  CI (99.9%): [1.268, 4.821] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.829 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.004 ms/op
Iteration   1: 3.151 ±(99.9%) 0.002 ms/op
Iteration   2: 3.142 ±(99.9%) 0.003 ms/op
Iteration   3: 3.094 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.129 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (3.094, 3.129, 3.151), stdev = 0.030
  CI (99.9%): [2.578, 3.680] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.757 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.699 ±(99.9%) 0.007 ms/op
Iteration   1: 3.709 ±(99.9%) 0.009 ms/op
Iteration   2: 3.678 ±(99.9%) 0.006 ms/op
Iteration   3: 3.701 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.696 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (3.678, 3.696, 3.709), stdev = 0.016
  CI (99.9%): [3.399, 3.993] (assumes normal distribution)


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
# Warmup Iteration   1: 7.673 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.522 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.009 ms/op
Iteration   1: 3.167 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  13.157 ms/op
                 createUser·p0.9999: 20.251 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   2: 3.106 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.277 ms/op
                 createUser·p0.95:   3.559 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  18.612 ms/op
                 createUser·p0.9999: 22.348 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   3: 3.096 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.248 ms/op
                 createUser·p0.95:   3.420 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  14.833 ms/op
                 createUser·p0.9999: 17.859 ms/op
                 createUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 307206
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24402 
    [ 2.500,  5.000) = 277613 
    [ 5.000,  7.500) = 4243 
    [ 7.500, 10.000) = 414 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     15.630 ms/op
     p(99.9900) =     21.472 ms/op
     p(99.9990) =     23.165 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.917 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.299 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.303 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.162 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   4.636 ms/op
                 existUser·p0.999:  8.384 ms/op
                 existUser·p0.9999: 18.788 ms/op
                 existUser·p1.00:   19.071 ms/op

Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.046 ms/op
                 existUser·p0.999:  11.300 ms/op
                 existUser·p0.9999: 19.431 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  13.697 ms/op
                 existUser·p0.9999: 19.917 ms/op
                 existUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311472
  mean =      3.080 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23206 
    [ 2.500,  5.000) = 284469 
    [ 5.000,  7.500) = 3150 
    [ 7.500, 10.000) = 290 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      5.218 ms/op
     p(99.9000) =     12.481 ms/op
     p(99.9900) =     19.590 ms/op
     p(99.9990) =     20.527 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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
# Warmup Iteration   1: 8.679 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.603 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.296 ±(99.9%) 0.009 ms/op
Iteration   1: 3.215 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  14.154 ms/op
                 getUser·p0.9999: 20.514 ms/op
                 getUser·p1.00:   21.692 ms/op

Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.479 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  9.383 ms/op
                 getUser·p0.9999: 20.047 ms/op
                 getUser·p1.00:   20.972 ms/op

Iteration   3: 3.293 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  11.222 ms/op
                 getUser·p0.9999: 22.381 ms/op
                 getUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298878
  mean =      3.209 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7194 
    [ 2.500,  5.000) = 283451 
    [ 5.000,  7.500) = 7242 
    [ 7.500, 10.000) = 596 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 173 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     13.668 ms/op
     p(99.9900) =     21.266 ms/op
     p(99.9990) =     23.155 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 9.115 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.035 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.738 ±(99.9%) 0.011 ms/op
Iteration   1: 3.709 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.591 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.728 ms/op
                 listUser·p0.999:  14.090 ms/op
                 listUser·p0.9999: 19.444 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   2: 3.793 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  12.403 ms/op
                 listUser·p0.9999: 16.796 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   3: 3.749 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.075 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  12.594 ms/op
                 listUser·p0.9999: 15.507 ms/op
                 listUser·p1.00:   15.548 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255928
  mean =      3.750 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 248677 
    [ 5.000,  7.500) = 5421 
    [ 7.500, 10.000) = 1158 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.591 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.985 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     17.872 ms/op
     p(99.9990) =     19.653 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.833 ± 4.978  ops/ms
ClientPb.existUser                       thrpt       3  10.103 ± 4.829  ops/ms
ClientPb.getUser                         thrpt       3  10.147 ± 2.809  ops/ms
ClientPb.listUser                        thrpt       3   8.424 ± 5.227  ops/ms
ClientPb.createUser                       avgt       3   3.180 ± 2.263   ms/op
ClientPb.existUser                        avgt       3   3.044 ± 1.777   ms/op
ClientPb.getUser                          avgt       3   3.129 ± 0.551   ms/op
ClientPb.listUser                         avgt       3   3.696 ± 0.297   ms/op
ClientPb.createUser                     sample  307206   3.123 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.002           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.571           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.630           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.472           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.233           ms/op
ClientPb.existUser                      sample  311472   3.080 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.229           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.218           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.481           ms/op
ClientPb.existUser:existUser·p0.9999    sample          19.590           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.103           ms/op
ClientPb.getUser                        sample  298878   3.209 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.044           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.551           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.100           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.160           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.668           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.266           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.182           ms/op
ClientPb.listUser                       sample  255928   3.750 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.591           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.985           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.664           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.872           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.054           ms/op
