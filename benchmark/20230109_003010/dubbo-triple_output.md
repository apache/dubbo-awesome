# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.248 ops/ms
# Warmup Iteration   2: 5.777 ops/ms
# Warmup Iteration   3: 9.059 ops/ms
Iteration   1: 9.463 ops/ms
Iteration   2: 9.596 ops/ms
Iteration   3: 9.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.562 ±(99.9%) 1.588 ops/ms [Average]
  (min, avg, max) = (9.463, 9.562, 9.626), stdev = 0.087
  CI (99.9%): [7.973, 11.150] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.122 ops/ms
# Warmup Iteration   2: 8.752 ops/ms
# Warmup Iteration   3: 9.901 ops/ms
Iteration   1: 9.818 ops/ms
Iteration   2: 10.190 ops/ms
Iteration   3: 9.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.912 ±(99.9%) 4.471 ops/ms [Average]
  (min, avg, max) = (9.727, 9.912, 10.190), stdev = 0.245
  CI (99.9%): [5.441, 14.383] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.157 ops/ms
# Warmup Iteration   2: 9.015 ops/ms
# Warmup Iteration   3: 9.493 ops/ms
Iteration   1: 9.815 ops/ms
Iteration   2: 10.218 ops/ms
Iteration   3: 9.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.983 ±(99.9%) 3.824 ops/ms [Average]
  (min, avg, max) = (9.815, 9.983, 10.218), stdev = 0.210
  CI (99.9%): [6.159, 13.807] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.876 ops/ms
# Warmup Iteration   2: 7.582 ops/ms
# Warmup Iteration   3: 8.325 ops/ms
Iteration   1: 8.453 ops/ms
Iteration   2: 8.415 ops/ms
Iteration   3: 8.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.432 ±(99.9%) 0.356 ops/ms [Average]
  (min, avg, max) = (8.415, 8.432, 8.453), stdev = 0.019
  CI (99.9%): [8.077, 8.788] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.805 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.005 ms/op
Iteration   1: 3.259 ±(99.9%) 0.001 ms/op
Iteration   2: 3.175 ±(99.9%) 0.004 ms/op
Iteration   3: 3.312 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.249 ±(99.9%) 1.260 ms/op [Average]
  (min, avg, max) = (3.175, 3.249, 3.312), stdev = 0.069
  CI (99.9%): [1.989, 4.509] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.862 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.386 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.005 ms/op
Iteration   1: 3.094 ±(99.9%) 0.006 ms/op
Iteration   2: 3.250 ±(99.9%) 0.004 ms/op
Iteration   3: 3.101 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.149 ±(99.9%) 1.603 ms/op [Average]
  (min, avg, max) = (3.094, 3.149, 3.250), stdev = 0.088
  CI (99.9%): [1.545, 4.752] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.586 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.005 ms/op
Iteration   1: 3.266 ±(99.9%) 0.005 ms/op
Iteration   2: 3.381 ±(99.9%) 0.005 ms/op
Iteration   3: 3.228 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.292 ±(99.9%) 1.446 ms/op [Average]
  (min, avg, max) = (3.228, 3.292, 3.381), stdev = 0.079
  CI (99.9%): [1.845, 4.738] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.804 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.006 ms/op
Iteration   1: 3.827 ±(99.9%) 0.004 ms/op
Iteration   2: 3.703 ±(99.9%) 0.013 ms/op
Iteration   3: 3.732 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.754 ±(99.9%) 1.186 ms/op [Average]
  (min, avg, max) = (3.703, 3.754, 3.827), stdev = 0.065
  CI (99.9%): [2.568, 4.940] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.155 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.009 ms/op
Iteration   1: 3.172 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  19.104 ms/op
                 createUser·p0.9999: 24.832 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   2: 3.393 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  18.300 ms/op
                 createUser·p0.9999: 25.676 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   3: 3.194 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  16.677 ms/op
                 createUser·p0.9999: 23.921 ms/op
                 createUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295243
  mean =      3.250 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11481 
    [ 2.500,  5.000) = 278163 
    [ 5.000,  7.500) = 4771 
    [ 7.500, 10.000) = 405 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     17.982 ms/op
     p(99.9900) =     25.035 ms/op
     p(99.9990) =     26.929 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.072 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.322 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.009 ms/op
Iteration   1: 3.128 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  10.349 ms/op
                 existUser·p0.9999: 20.734 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   2: 3.133 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  13.658 ms/op
                 existUser·p0.9999: 24.791 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   3: 3.111 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.387 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  14.696 ms/op
                 existUser·p0.9999: 20.840 ms/op
                 existUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307251
  mean =      3.124 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20440 
    [ 2.500,  5.000) = 280940 
    [ 5.000,  7.500) = 4936 
    [ 7.500, 10.000) = 419 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     13.852 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     25.908 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.440 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.469 ±(99.9%) 0.011 ms/op
Iteration   1: 3.260 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  19.326 ms/op
                 getUser·p0.9999: 28.029 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   2: 3.264 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  10.893 ms/op
                 getUser·p0.9999: 22.190 ms/op
                 getUser·p1.00:   22.905 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.415 ms/op
                 getUser·p0.999:  17.596 ms/op
                 getUser·p0.9999: 23.593 ms/op
                 getUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297118
  mean =      3.230 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19387 
    [ 2.500,  5.000) = 270646 
    [ 5.000,  7.500) = 6141 
    [ 7.500, 10.000) = 395 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     26.846 ms/op
     p(99.9990) =     28.575 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.460 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.773 ±(99.9%) 0.013 ms/op
Iteration   1: 3.758 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.450 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  15.428 ms/op
                 listUser·p0.9999: 25.410 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   2: 3.778 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  13.074 ms/op
                 listUser·p0.9999: 14.762 ms/op
                 listUser·p1.00:   15.188 ms/op

Iteration   3: 3.872 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.793 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252386
  mean =      3.802 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 244563 
    [ 5.000,  7.500) = 5956 
    [ 7.500, 10.000) = 1168 
    [10.000, 12.500) = 228 
    [12.500, 15.000) = 260 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.450 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     14.008 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     25.738 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.562 ± 1.588  ops/ms
ClientPb.existUser                       thrpt       3   9.912 ± 4.471  ops/ms
ClientPb.getUser                         thrpt       3   9.983 ± 3.824  ops/ms
ClientPb.listUser                        thrpt       3   8.432 ± 0.356  ops/ms
ClientPb.createUser                       avgt       3   3.249 ± 1.260   ms/op
ClientPb.existUser                        avgt       3   3.149 ± 1.603   ms/op
ClientPb.getUser                          avgt       3   3.292 ± 1.446   ms/op
ClientPb.listUser                         avgt       3   3.754 ± 1.186   ms/op
ClientPb.createUser                     sample  295243   3.250 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.090           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.571           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.982           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.035           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.344           ms/op
ClientPb.existUser                      sample  307251   3.124 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.999           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.400           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.852           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.970           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.149           ms/op
ClientPb.getUser                        sample  297118   3.230 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.862           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.666           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.825           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.022           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.846           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.901           ms/op
ClientPb.listUser                       sample  252386   3.802 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.450           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.914           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.008           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.872           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.854           ms/op
