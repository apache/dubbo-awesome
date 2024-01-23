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
# Warmup Iteration   1: 4.673 ops/ms
# Warmup Iteration   2: 12.020 ops/ms
# Warmup Iteration   3: 12.203 ops/ms
Iteration   1: 12.457 ops/ms
Iteration   2: 12.484 ops/ms
Iteration   3: 12.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.542 ±(99.9%) 2.264 ops/ms [Average]
  (min, avg, max) = (12.457, 12.542, 12.684), stdev = 0.124
  CI (99.9%): [10.278, 14.806] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.107 ops/ms
# Warmup Iteration   2: 13.310 ops/ms
# Warmup Iteration   3: 13.164 ops/ms
Iteration   1: 13.260 ops/ms
Iteration   2: 13.384 ops/ms
Iteration   3: 13.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.287 ±(99.9%) 1.570 ops/ms [Average]
  (min, avg, max) = (13.218, 13.287, 13.384), stdev = 0.086
  CI (99.9%): [11.717, 14.858] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.862 ops/ms
# Warmup Iteration   2: 12.531 ops/ms
# Warmup Iteration   3: 12.851 ops/ms
Iteration   1: 12.816 ops/ms
Iteration   2: 13.023 ops/ms
Iteration   3: 13.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.959 ±(99.9%) 2.262 ops/ms [Average]
  (min, avg, max) = (12.816, 12.959, 13.038), stdev = 0.124
  CI (99.9%): [10.697, 15.221] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.450 ops/ms
# Warmup Iteration   2: 10.729 ops/ms
# Warmup Iteration   3: 10.763 ops/ms
Iteration   1: 10.746 ops/ms
Iteration   2: 10.689 ops/ms
Iteration   3: 10.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.727 ±(99.9%) 0.591 ops/ms [Average]
  (min, avg, max) = (10.689, 10.727, 10.746), stdev = 0.032
  CI (99.9%): [10.135, 11.318] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.126 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.670 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.584 ±(99.9%) 0.004 ms/op
Iteration   1: 2.578 ±(99.9%) 0.004 ms/op
Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
Iteration   3: 2.571 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.570 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (2.559, 2.570, 2.578), stdev = 0.010
  CI (99.9%): [2.393, 2.746] (assumes normal distribution)


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
# Warmup Iteration   1: 3.641 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.004 ms/op
Iteration   1: 2.425 ±(99.9%) 0.004 ms/op
Iteration   2: 2.422 ±(99.9%) 0.004 ms/op
Iteration   3: 2.405 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.417 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (2.405, 2.417, 2.425), stdev = 0.011
  CI (99.9%): [2.220, 2.615] (assumes normal distribution)


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.004 ms/op
Iteration   1: 2.466 ±(99.9%) 0.004 ms/op
Iteration   2: 2.450 ±(99.9%) 0.003 ms/op
Iteration   3: 2.485 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.467 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (2.450, 2.467, 2.485), stdev = 0.018
  CI (99.9%): [2.145, 2.789] (assumes normal distribution)


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
# Warmup Iteration   1: 4.513 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.005 ms/op
Iteration   1: 3.027 ±(99.9%) 0.005 ms/op
Iteration   2: 3.024 ±(99.9%) 0.005 ms/op
Iteration   3: 3.060 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.037 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (3.024, 3.037, 3.060), stdev = 0.020
  CI (99.9%): [2.679, 3.395] (assumes normal distribution)


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.920 ms/op
                 createUser·p0.999:  11.133 ms/op
                 createUser·p0.9999: 13.058 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  8.731 ms/op
                 createUser·p0.9999: 12.380 ms/op
                 createUser·p1.00:   12.714 ms/op

Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  9.060 ms/op
                 createUser·p0.9999: 11.472 ms/op
                 createUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381644
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 184387 
    [ 2.500,  3.750) = 192922 
    [ 3.750,  5.000) = 3465 
    [ 5.000,  6.250) = 340 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     12.812 ms/op
     p(99.9990) =     13.810 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 3.588 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.414 ±(99.9%) 0.005 ms/op
Iteration   1: 2.410 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  5.710 ms/op
                 existUser·p0.9999: 13.562 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.965 ms/op
                 existUser·p0.999:  7.192 ms/op
                 existUser·p0.9999: 12.747 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  8.091 ms/op
                 existUser·p0.9999: 11.667 ms/op
                 existUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393932
  mean =      2.434 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 196732 
    [ 2.500,  3.750) = 193677 
    [ 3.750,  5.000) = 2681 
    [ 5.000,  6.250) = 373 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      6.578 ms/op
     p(99.9900) =     12.875 ms/op
     p(99.9990) =     14.321 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.006 ms/op
Iteration   1: 2.473 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  6.615 ms/op
                 getUser·p0.9999: 27.696 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.064 ms/op
                 getUser·p0.99:   3.564 ms/op
                 getUser·p0.999:  6.295 ms/op
                 getUser·p0.9999: 11.838 ms/op
                 getUser·p1.00:   12.812 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   4.010 ms/op
                 getUser·p0.999:  6.430 ms/op
                 getUser·p0.9999: 11.174 ms/op
                 getUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389501
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 194915 
    [ 2.500,  5.000) = 193834 
    [ 5.000,  7.500) = 368 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      6.418 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     28.155 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 4.595 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
Iteration   1: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.219 ms/op
                 listUser·p0.9999: 10.482 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   2: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.537 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.357 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  10.001 ms/op
                 listUser·p0.9999: 10.977 ms/op
                 listUser·p1.00:   11.190 ms/op

Iteration   3: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 10.431 ms/op
                 listUser·p1.00:   11.092 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319674
  mean =      3.000 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 92458 
    [ 2.500,  3.750) = 188615 
    [ 3.750,  5.000) = 31841 
    [ 5.000,  6.250) = 5420 
    [ 6.250,  7.500) = 551 
    [ 7.500,  8.750) = 230 
    [ 8.750, 10.000) = 264 
    [10.000, 11.250) = 180 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     10.798 ms/op
     p(99.9990) =     11.207 ms/op
     p(99.9999) =     11.370 ms/op
    p(100.0000) =     11.370 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.542 ± 2.264  ops/ms
ClientPb.existUser                       thrpt       3  13.287 ± 1.570  ops/ms
ClientPb.getUser                         thrpt       3  12.959 ± 2.262  ops/ms
ClientPb.listUser                        thrpt       3  10.727 ± 0.591  ops/ms
ClientPb.createUser                       avgt       3   2.570 ± 0.177   ms/op
ClientPb.existUser                        avgt       3   2.417 ± 0.197   ms/op
ClientPb.getUser                          avgt       3   2.467 ± 0.322   ms/op
ClientPb.listUser                         avgt       3   3.037 ± 0.358   ms/op
ClientPb.createUser                     sample  381644   2.513 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.831           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.011           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.812           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.418           ms/op
ClientPb.existUser                      sample  393932   2.434 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.827           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.578           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.875           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.467           ms/op
ClientPb.getUser                        sample  389501   2.462 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.885           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.418           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.550           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.246           ms/op
ClientPb.listUser                       sample  319674   3.000 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.537           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.798           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.370           ms/op
