# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.991 ops/ms
# Warmup Iteration   2: 11.936 ops/ms
# Warmup Iteration   3: 12.222 ops/ms
Iteration   1: 12.578 ops/ms
Iteration   2: 12.423 ops/ms
Iteration   3: 12.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.459 ±(99.9%) 1.930 ops/ms [Average]
  (min, avg, max) = (12.375, 12.459, 12.578), stdev = 0.106
  CI (99.9%): [10.529, 14.389] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.406 ops/ms
# Warmup Iteration   2: 13.247 ops/ms
# Warmup Iteration   3: 13.279 ops/ms
Iteration   1: 13.200 ops/ms
Iteration   2: 13.321 ops/ms
Iteration   3: 13.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.271 ±(99.9%) 1.158 ops/ms [Average]
  (min, avg, max) = (13.200, 13.271, 13.321), stdev = 0.063
  CI (99.9%): [12.113, 14.429] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.091 ops/ms
# Warmup Iteration   2: 12.757 ops/ms
# Warmup Iteration   3: 12.794 ops/ms
Iteration   1: 12.862 ops/ms
Iteration   2: 13.149 ops/ms
Iteration   3: 13.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.029 ±(99.9%) 2.723 ops/ms [Average]
  (min, avg, max) = (12.862, 13.029, 13.149), stdev = 0.149
  CI (99.9%): [10.306, 15.753] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.505 ops/ms
# Warmup Iteration   2: 10.447 ops/ms
# Warmup Iteration   3: 10.485 ops/ms
Iteration   1: 10.572 ops/ms
Iteration   2: 10.493 ops/ms
Iteration   3: 10.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.516 ±(99.9%) 0.883 ops/ms [Average]
  (min, avg, max) = (10.484, 10.516, 10.572), stdev = 0.048
  CI (99.9%): [9.633, 11.399] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.070 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
Iteration   3: 2.557 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.532 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (2.507, 2.532, 2.557), stdev = 0.025
  CI (99.9%): [2.074, 2.991] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.547 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.004 ms/op
Iteration   1: 2.459 ±(99.9%) 0.004 ms/op
Iteration   2: 2.419 ±(99.9%) 0.004 ms/op
Iteration   3: 2.417 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.432 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (2.417, 2.432, 2.459), stdev = 0.023
  CI (99.9%): [2.006, 2.857] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.885 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.004 ms/op
Iteration   1: 2.484 ±(99.9%) 0.004 ms/op
Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.473 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (2.467, 2.473, 2.484), stdev = 0.010
  CI (99.9%): [2.298, 2.648] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.569 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
Iteration   1: 2.986 ±(99.9%) 0.005 ms/op
Iteration   2: 2.982 ±(99.9%) 0.005 ms/op
Iteration   3: 2.965 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.977 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.965, 2.977, 2.986), stdev = 0.011
  CI (99.9%): [2.771, 3.184] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.990 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.713 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.006 ms/op
Iteration   1: 2.561 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   4.022 ms/op
                 createUser·p0.999:  11.324 ms/op
                 createUser·p0.9999: 13.189 ms/op
                 createUser·p1.00:   13.877 ms/op

Iteration   2: 2.552 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  8.761 ms/op
                 createUser·p0.9999: 14.426 ms/op
                 createUser·p1.00:   14.975 ms/op

Iteration   3: 2.573 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  8.176 ms/op
                 createUser·p0.9999: 10.217 ms/op
                 createUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374299
  mean =      2.562 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 179296 
    [ 2.500,  3.750) = 190678 
    [ 3.750,  5.000) = 3282 
    [ 5.000,  6.250) = 519 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      8.212 ms/op
     p(99.9900) =     13.250 ms/op
     p(99.9990) =     14.901 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.002 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  6.221 ms/op
                 existUser·p0.9999: 14.254 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  6.922 ms/op
                 existUser·p0.9999: 13.633 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  7.159 ms/op
                 existUser·p0.9999: 12.534 ms/op
                 existUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390751
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 192590 
    [ 2.500,  3.750) = 194718 
    [ 3.750,  5.000) = 2643 
    [ 5.000,  6.250) = 344 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      6.873 ms/op
     p(99.9900) =     13.746 ms/op
     p(99.9990) =     14.682 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.791 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.006 ms/op
Iteration   1: 2.418 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.040 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   2.933 ms/op
                 getUser·p0.95:   3.031 ms/op
                 getUser·p0.99:   3.523 ms/op
                 getUser·p0.999:  7.101 ms/op
                 getUser·p0.9999: 13.304 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  6.036 ms/op
                 getUser·p0.9999: 12.565 ms/op
                 getUser·p1.00:   13.271 ms/op

Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.897 ms/op
                 getUser·p0.9999: 10.947 ms/op
                 getUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392764
  mean =      2.442 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 198956 
    [ 2.500,  3.750) = 188998 
    [ 3.750,  5.000) = 3660 
    [ 5.000,  6.250) = 537 
    [ 6.250,  7.500) = 126 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =      7.716 ms/op
     p(99.9900) =     12.747 ms/op
     p(99.9990) =     13.436 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.619 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.009 ms/op
Iteration   1: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  8.859 ms/op
                 listUser·p0.9999: 11.798 ms/op
                 listUser·p1.00:   12.222 ms/op

Iteration   2: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  8.716 ms/op
                 listUser·p0.9999: 11.256 ms/op
                 listUser·p1.00:   12.108 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.199 ms/op
                 listUser·p0.9999: 11.728 ms/op
                 listUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318797
  mean =      3.008 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 92611 
    [ 2.500,  3.750) = 186375 
    [ 3.750,  5.000) = 32715 
    [ 5.000,  6.250) = 5684 
    [ 6.250,  7.500) = 624 
    [ 7.500,  8.750) = 320 
    [ 8.750, 10.000) = 247 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     11.491 ms/op
     p(99.9990) =     12.141 ms/op
     p(99.9999) =     12.222 ms/op
    p(100.0000) =     12.222 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.459 ± 1.930  ops/ms
ClientPb.existUser                       thrpt       3  13.271 ± 1.158  ops/ms
ClientPb.getUser                         thrpt       3  13.029 ± 2.723  ops/ms
ClientPb.listUser                        thrpt       3  10.516 ± 0.883  ops/ms
ClientPb.createUser                       avgt       3   2.532 ± 0.458   ms/op
ClientPb.existUser                        avgt       3   2.432 ± 0.426   ms/op
ClientPb.getUser                          avgt       3   2.473 ± 0.175   ms/op
ClientPb.listUser                         avgt       3   2.977 ± 0.207   ms/op
ClientPb.createUser                     sample  374299   2.562 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.958           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.212           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.250           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.975           ms/op
ClientPb.existUser                      sample  390751   2.455 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.692           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.873           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.746           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.073           ms/op
ClientPb.getUser                        sample  392764   2.442 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.713           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.966           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.716           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.747           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.681           ms/op
ClientPb.listUser                       sample  318797   3.008 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.869           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.831           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.491           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.222           ms/op
