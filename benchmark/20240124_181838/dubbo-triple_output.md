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
# Warmup Iteration   1: 4.822 ops/ms
# Warmup Iteration   2: 11.604 ops/ms
# Warmup Iteration   3: 12.209 ops/ms
Iteration   1: 12.528 ops/ms
Iteration   2: 12.358 ops/ms
Iteration   3: 12.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.497 ±(99.9%) 2.300 ops/ms [Average]
  (min, avg, max) = (12.358, 12.497, 12.604), stdev = 0.126
  CI (99.9%): [10.197, 14.797] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 7.656 ops/ms
# Warmup Iteration   2: 12.677 ops/ms
# Warmup Iteration   3: 12.372 ops/ms
Iteration   1: 12.771 ops/ms
Iteration   2: 12.793 ops/ms
Iteration   3: 12.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.710 ±(99.9%) 2.282 ops/ms [Average]
  (min, avg, max) = (12.566, 12.710, 12.793), stdev = 0.125
  CI (99.9%): [10.428, 14.992] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.366 ops/ms
# Warmup Iteration   2: 12.360 ops/ms
# Warmup Iteration   3: 12.733 ops/ms
Iteration   1: 12.889 ops/ms
Iteration   2: 12.908 ops/ms
Iteration   3: 12.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.871 ±(99.9%) 0.901 ops/ms [Average]
  (min, avg, max) = (12.815, 12.871, 12.908), stdev = 0.049
  CI (99.9%): [11.970, 13.771] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.074 ops/ms
# Warmup Iteration   2: 10.203 ops/ms
# Warmup Iteration   3: 10.288 ops/ms
Iteration   1: 10.227 ops/ms
Iteration   2: 10.347 ops/ms
Iteration   3: 10.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.310 ±(99.9%) 1.321 ops/ms [Average]
  (min, avg, max) = (10.227, 10.310, 10.357), stdev = 0.072
  CI (99.9%): [8.989, 11.631] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.450 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.004 ms/op
Iteration   1: 2.551 ±(99.9%) 0.004 ms/op
Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
Iteration   3: 2.537 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.537 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.525, 2.537, 2.551), stdev = 0.013
  CI (99.9%): [2.300, 2.775] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.003 ms/op
Iteration   1: 2.473 ±(99.9%) 0.003 ms/op
Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
Iteration   3: 2.475 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.471 ±(99.9%) 0.098 ms/op [Average]
  (min, avg, max) = (2.465, 2.471, 2.475), stdev = 0.005
  CI (99.9%): [2.373, 2.569] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.237 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.602 ±(99.9%) 0.005 ms/op
Iteration   1: 2.527 ±(99.9%) 0.003 ms/op
Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
Iteration   3: 2.606 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.556 ±(99.9%) 0.785 ms/op [Average]
  (min, avg, max) = (2.527, 2.556, 2.606), stdev = 0.043
  CI (99.9%): [1.771, 3.341] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 5.354 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
Iteration   1: 3.065 ±(99.9%) 0.006 ms/op
Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
Iteration   3: 3.074 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.076 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (3.065, 3.076, 3.089), stdev = 0.012
  CI (99.9%): [2.848, 3.304] (assumes normal distribution)


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
# Warmup Iteration   1: 4.321 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.626 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
Iteration   1: 2.547 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  12.591 ms/op
                 createUser·p0.9999: 14.605 ms/op
                 createUser·p1.00:   15.155 ms/op

Iteration   2: 2.578 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.305 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  10.911 ms/op
                 createUser·p0.9999: 14.680 ms/op
                 createUser·p1.00:   15.057 ms/op

Iteration   3: 2.569 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   3.932 ms/op
                 createUser·p0.999:  8.585 ms/op
                 createUser·p0.9999: 11.141 ms/op
                 createUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373857
  mean =      2.564 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 175416 
    [ 2.500,  3.750) = 193814 
    [ 3.750,  5.000) = 3693 
    [ 5.000,  6.250) = 414 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 93 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     14.520 ms/op
     p(99.9990) =     14.968 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.516 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.211 ms/op
                 existUser·p0.99:   3.903 ms/op
                 existUser·p0.999:  11.168 ms/op
                 existUser·p0.9999: 14.406 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   2: 2.526 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   3.864 ms/op
                 existUser·p0.999:  9.842 ms/op
                 existUser·p0.9999: 13.681 ms/op
                 existUser·p1.00:   15.057 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.068 ms/op
                 existUser·p0.95:   3.207 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  7.696 ms/op
                 existUser·p0.9999: 12.265 ms/op
                 existUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 380411
  mean =      2.521 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 181935 
    [ 2.500,  3.750) = 193329 
    [ 3.750,  5.000) = 4041 
    [ 5.000,  6.250) = 585 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 148 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      7.834 ms/op
     p(99.9900) =     13.823 ms/op
     p(99.9990) =     15.044 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 4.329 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.679 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.006 ms/op
Iteration   1: 2.561 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   3.996 ms/op
                 getUser·p0.999:  5.695 ms/op
                 getUser·p0.9999: 14.387 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   2: 2.613 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   2.634 ms/op
                 getUser·p0.90:   3.191 ms/op
                 getUser·p0.95:   3.416 ms/op
                 getUser·p0.99:   5.054 ms/op
                 getUser·p0.999:  8.935 ms/op
                 getUser·p0.9999: 14.591 ms/op
                 getUser·p1.00:   14.959 ms/op

Iteration   3: 2.553 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  8.381 ms/op
                 getUser·p0.9999: 10.961 ms/op
                 getUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 372381
  mean =      2.576 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 177705 
    [ 2.500,  3.750) = 187776 
    [ 3.750,  5.000) = 5052 
    [ 5.000,  6.250) = 1333 
    [ 6.250,  7.500) = 106 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.146 ms/op
     p(95.0000) =      3.297 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =      7.159 ms/op
     p(99.9900) =     13.919 ms/op
     p(99.9990) =     15.499 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 5.178 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.009 ms/op
Iteration   1: 3.138 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.001 ms/op
                 listUser·p0.50:   3.072 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.005 ms/op
                 listUser·p0.999:  9.194 ms/op
                 listUser·p0.9999: 10.519 ms/op
                 listUser·p1.00:   10.748 ms/op

Iteration   2: 3.117 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.047 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  9.878 ms/op
                 listUser·p0.9999: 12.382 ms/op
                 listUser·p1.00:   12.878 ms/op

Iteration   3: 3.124 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  9.972 ms/op
                 listUser·p0.9999: 11.862 ms/op
                 listUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 306758
  mean =      3.126 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 73672 
    [ 2.500,  3.750) = 184774 
    [ 3.750,  5.000) = 38843 
    [ 5.000,  6.250) = 7543 
    [ 6.250,  7.500) = 1158 
    [ 7.500,  8.750) = 216 
    [ 8.750, 10.000) = 247 
    [10.000, 11.250) = 166 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     11.851 ms/op
     p(99.9990) =     12.517 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.497 ± 2.300  ops/ms
ClientPb.existUser                       thrpt       3  12.710 ± 2.282  ops/ms
ClientPb.getUser                         thrpt       3  12.871 ± 0.901  ops/ms
ClientPb.listUser                        thrpt       3  10.310 ± 1.321  ops/ms
ClientPb.createUser                       avgt       3   2.537 ± 0.237   ms/op
ClientPb.existUser                        avgt       3   2.471 ± 0.098   ms/op
ClientPb.getUser                          avgt       3   2.556 ± 0.785   ms/op
ClientPb.listUser                         avgt       3   3.076 ± 0.228   ms/op
ClientPb.createUser                     sample  373857   2.564 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.924           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.602           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.520           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.155           ms/op
ClientPb.existUser                      sample  380411   2.521 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.723           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.589           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.834           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.823           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.188           ms/op
ClientPb.getUser                        sample  372381   2.576 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.670           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.609           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.159           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.919           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.516           ms/op
ClientPb.listUser                       sample  306758   3.126 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.877           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.056           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.055           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.849           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.851           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.878           ms/op
