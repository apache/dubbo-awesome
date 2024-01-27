# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.320 ops/ms
# Warmup Iteration   2: 12.308 ops/ms
# Warmup Iteration   3: 12.614 ops/ms
Iteration   1: 12.586 ops/ms
Iteration   2: 12.818 ops/ms
Iteration   3: 12.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.746 ±(99.9%) 2.524 ops/ms [Average]
  (min, avg, max) = (12.586, 12.746, 12.833), stdev = 0.138
  CI (99.9%): [10.222, 15.270] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.752 ops/ms
# Warmup Iteration   2: 13.353 ops/ms
# Warmup Iteration   3: 13.223 ops/ms
Iteration   1: 13.403 ops/ms
Iteration   2: 13.470 ops/ms
Iteration   3: 13.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.393 ±(99.9%) 1.516 ops/ms [Average]
  (min, avg, max) = (13.305, 13.393, 13.470), stdev = 0.083
  CI (99.9%): [11.877, 14.909] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.064 ops/ms
# Warmup Iteration   2: 13.191 ops/ms
# Warmup Iteration   3: 13.021 ops/ms
Iteration   1: 13.139 ops/ms
Iteration   2: 13.011 ops/ms
Iteration   3: 13.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.132 ±(99.9%) 2.153 ops/ms [Average]
  (min, avg, max) = (13.011, 13.132, 13.247), stdev = 0.118
  CI (99.9%): [10.979, 15.285] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.926 ops/ms
# Warmup Iteration   2: 10.797 ops/ms
# Warmup Iteration   3: 10.884 ops/ms
Iteration   1: 10.829 ops/ms
Iteration   2: 10.567 ops/ms
Iteration   3: 10.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.769 ±(99.9%) 3.264 ops/ms [Average]
  (min, avg, max) = (10.567, 10.769, 10.910), stdev = 0.179
  CI (99.9%): [7.505, 14.033] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.542 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.508 ±(99.9%) 0.004 ms/op
Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.501 ±(99.9%) 0.151 ms/op [Average]
  (min, avg, max) = (2.492, 2.501, 2.508), stdev = 0.008
  CI (99.9%): [2.350, 2.652] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.651 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.417 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.399 ±(99.9%) 0.003 ms/op
Iteration   1: 2.387 ±(99.9%) 0.004 ms/op
Iteration   2: 2.360 ±(99.9%) 0.003 ms/op
Iteration   3: 2.403 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.383 ±(99.9%) 0.394 ms/op [Average]
  (min, avg, max) = (2.360, 2.383, 2.403), stdev = 0.022
  CI (99.9%): [1.989, 2.778] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.700 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.004 ms/op
Iteration   1: 2.474 ±(99.9%) 0.003 ms/op
Iteration   2: 2.439 ±(99.9%) 0.004 ms/op
Iteration   3: 2.441 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.451 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (2.439, 2.451, 2.474), stdev = 0.020
  CI (99.9%): [2.089, 2.814] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.425 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.006 ms/op
Iteration   2: 2.956 ±(99.9%) 0.005 ms/op
Iteration   3: 2.941 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.945 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.940, 2.945, 2.956), stdev = 0.009
  CI (99.9%): [2.777, 3.114] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.974 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  7.048 ms/op
                 createUser·p0.9999: 12.960 ms/op
                 createUser·p1.00:   13.271 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   3.469 ms/op
                 createUser·p0.999:  5.693 ms/op
                 createUser·p0.9999: 11.615 ms/op
                 createUser·p1.00:   12.583 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  7.857 ms/op
                 createUser·p0.9999: 10.328 ms/op
                 createUser·p1.00:   13.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389547
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 193203 
    [ 2.500,  3.750) = 193089 
    [ 3.750,  5.000) = 2434 
    [ 5.000,  6.250) = 349 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 122 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      6.946 ms/op
     p(99.9900) =     12.240 ms/op
     p(99.9990) =     13.222 ms/op
     p(99.9999) =     13.386 ms/op
    p(100.0000) =     13.386 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.655 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.428 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  6.077 ms/op
                 existUser·p0.9999: 13.162 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  7.148 ms/op
                 existUser·p0.9999: 10.436 ms/op
                 existUser·p1.00:   11.207 ms/op

Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  6.826 ms/op
                 existUser·p0.9999: 11.697 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392237
  mean =      2.444 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 192311 
    [ 2.500,  3.750) = 197002 
    [ 3.750,  5.000) = 2183 
    [ 5.000,  6.250) = 265 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.547 ms/op
     p(99.9000) =      6.930 ms/op
     p(99.9900) =     12.567 ms/op
     p(99.9990) =     13.797 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.722 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.006 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  5.780 ms/op
                 getUser·p0.9999: 12.992 ms/op
                 getUser·p1.00:   13.533 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  8.412 ms/op
                 getUser·p0.9999: 12.157 ms/op
                 getUser·p1.00:   12.288 ms/op

Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.953 ms/op
                 getUser·p0.95:   3.052 ms/op
                 getUser·p0.99:   3.527 ms/op
                 getUser·p0.999:  6.372 ms/op
                 getUser·p0.9999: 10.289 ms/op
                 getUser·p1.00:   10.584 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390822
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 196305 
    [ 2.500,  3.750) = 190070 
    [ 3.750,  5.000) = 3444 
    [ 5.000,  6.250) = 514 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      7.114 ms/op
     p(99.9900) =     12.523 ms/op
     p(99.9990) =     13.112 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.653 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.009 ms/op
Iteration   1: 2.926 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.765 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.752 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   5.362 ms/op
                 listUser·p0.999:  8.749 ms/op
                 listUser·p0.9999: 10.148 ms/op
                 listUser·p1.00:   10.863 ms/op

Iteration   2: 2.921 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.727 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   5.333 ms/op
                 listUser·p0.999:  9.217 ms/op
                 listUser·p0.9999: 11.716 ms/op
                 listUser·p1.00:   12.567 ms/op

Iteration   3: 2.936 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.674 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.341 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 11.320 ms/op
                 listUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 327581
  mean =      2.928 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 104819 
    [ 2.500,  3.750) = 189551 
    [ 3.750,  5.000) = 27364 
    [ 5.000,  6.250) = 4699 
    [ 6.250,  7.500) = 331 
    [ 7.500,  8.750) = 250 
    [ 8.750, 10.000) = 279 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     11.235 ms/op
     p(99.9990) =     12.517 ms/op
     p(99.9999) =     12.845 ms/op
    p(100.0000) =     12.845 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.746 ± 2.524  ops/ms
ClientPb.existUser                       thrpt       3  13.393 ± 1.516  ops/ms
ClientPb.getUser                         thrpt       3  13.132 ± 2.153  ops/ms
ClientPb.listUser                        thrpt       3  10.769 ± 3.264  ops/ms
ClientPb.createUser                       avgt       3   2.501 ± 0.151   ms/op
ClientPb.existUser                        avgt       3   2.383 ± 0.394   ms/op
ClientPb.getUser                          avgt       3   2.451 ± 0.362   ms/op
ClientPb.listUser                         avgt       3   2.945 ± 0.168   ms/op
ClientPb.createUser                     sample  389547   2.462 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.794           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.515           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.999   sample           6.946           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.240           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.386           ms/op
ClientPb.existUser                      sample  392237   2.444 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.798           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.930           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.567           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.861           ms/op
ClientPb.getUser                        sample  390822   2.454 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.891           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.982           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.114           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.523           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.533           ms/op
ClientPb.listUser                       sample  327581   2.928 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.674           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.756           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.341           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.028           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.235           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.845           ms/op
