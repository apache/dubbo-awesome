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
# Warmup Iteration   1: 1.570 ops/ms
# Warmup Iteration   2: 3.386 ops/ms
# Warmup Iteration   3: 6.943 ops/ms
Iteration   1: 7.701 ops/ms
Iteration   2: 8.073 ops/ms
Iteration   3: 8.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.972 ±(99.9%) 4.327 ops/ms [Average]
  (min, avg, max) = (7.701, 7.972, 8.142), stdev = 0.237
  CI (99.9%): [3.645, 12.299] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.163 ops/ms
# Warmup Iteration   2: 6.787 ops/ms
# Warmup Iteration   3: 7.548 ops/ms
Iteration   1: 8.140 ops/ms
Iteration   2: 8.428 ops/ms
Iteration   3: 8.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.235 ±(99.9%) 3.061 ops/ms [Average]
  (min, avg, max) = (8.135, 8.235, 8.428), stdev = 0.168
  CI (99.9%): [5.173, 11.296] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.205 ops/ms
# Warmup Iteration   2: 6.719 ops/ms
# Warmup Iteration   3: 7.814 ops/ms
Iteration   1: 7.508 ops/ms
Iteration   2: 8.153 ops/ms
Iteration   3: 8.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.987 ±(99.9%) 7.677 ops/ms [Average]
  (min, avg, max) = (7.508, 7.987, 8.299), stdev = 0.421
  CI (99.9%): [0.310, 15.664] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.014 ops/ms
# Warmup Iteration   2: 5.731 ops/ms
# Warmup Iteration   3: 6.350 ops/ms
Iteration   1: 6.561 ops/ms
Iteration   2: 6.877 ops/ms
Iteration   3: 6.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.650 ±(99.9%) 3.614 ops/ms [Average]
  (min, avg, max) = (6.512, 6.650, 6.877), stdev = 0.198
  CI (99.9%): [3.036, 10.264] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.905 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.612 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.205 ±(99.9%) 0.009 ms/op
Iteration   1: 4.042 ±(99.9%) 0.005 ms/op
Iteration   2: 4.042 ±(99.9%) 0.008 ms/op
Iteration   3: 4.009 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.031 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (4.009, 4.031, 4.042), stdev = 0.019
  CI (99.9%): [3.685, 4.376] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.998 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.688 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.005 ms/op
Iteration   1: 3.736 ±(99.9%) 0.013 ms/op
Iteration   2: 3.805 ±(99.9%) 0.006 ms/op
Iteration   3: 3.789 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.776 ±(99.9%) 0.657 ms/op [Average]
  (min, avg, max) = (3.736, 3.776, 3.805), stdev = 0.036
  CI (99.9%): [3.120, 4.433] (assumes normal distribution)


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
# Warmup Iteration   1: 13.083 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.898 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.003 ms/op
Iteration   1: 4.116 ±(99.9%) 0.008 ms/op
Iteration   2: 4.084 ±(99.9%) 0.004 ms/op
Iteration   3: 4.101 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.100 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (4.084, 4.100, 4.116), stdev = 0.016
  CI (99.9%): [3.808, 4.393] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.708 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.665 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.789 ±(99.9%) 0.006 ms/op
Iteration   1: 4.594 ±(99.9%) 0.013 ms/op
Iteration   2: 4.617 ±(99.9%) 0.013 ms/op
Iteration   3: 4.716 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.642 ±(99.9%) 1.182 ms/op [Average]
  (min, avg, max) = (4.594, 4.642, 4.716), stdev = 0.065
  CI (99.9%): [3.461, 5.824] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 14.711 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 5.211 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.462 ±(99.9%) 0.018 ms/op
Iteration   1: 4.020 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.872 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   7.753 ms/op
                 createUser·p0.999:  24.565 ms/op
                 createUser·p0.9999: 31.261 ms/op
                 createUser·p1.00:   32.801 ms/op

Iteration   2: 3.975 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.845 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  27.772 ms/op
                 createUser·p0.9999: 39.974 ms/op
                 createUser·p1.00:   40.894 ms/op

Iteration   3: 4.053 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.698 ms/op
                 createUser·p0.50:   4.018 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.915 ms/op
                 createUser·p0.99:   6.738 ms/op
                 createUser·p0.999:  21.922 ms/op
                 createUser·p0.9999: 31.435 ms/op
                 createUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238957
  mean =      4.015 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 228391 
    [ 5.000, 10.000) = 9789 
    [10.000, 15.000) = 445 
    [15.000, 20.000) = 42 
    [20.000, 25.000) = 54 
    [25.000, 30.000) = 121 
    [30.000, 35.000) = 83 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     24.677 ms/op
     p(99.9900) =     38.490 ms/op
     p(99.9990) =     40.843 ms/op
     p(99.9999) =     40.894 ms/op
    p(100.0000) =     40.894 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.346 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.425 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.012 ms/op
Iteration   1: 3.969 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.667 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   7.619 ms/op
                 existUser·p0.999:  10.001 ms/op
                 existUser·p0.9999: 25.359 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   2: 3.852 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.614 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.470 ms/op
                 existUser·p0.99:   6.783 ms/op
                 existUser·p0.999:  24.725 ms/op
                 existUser·p0.9999: 26.882 ms/op
                 existUser·p1.00:   27.886 ms/op

Iteration   3: 3.878 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.579 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   7.471 ms/op
                 existUser·p0.999:  10.174 ms/op
                 existUser·p0.9999: 28.762 ms/op
                 existUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246205
  mean =      3.899 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 451 
    [ 2.500,  5.000) = 237017 
    [ 5.000,  7.500) = 6566 
    [ 7.500, 10.000) = 1856 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 114 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.579 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     10.574 ms/op
     p(99.9900) =     28.140 ms/op
     p(99.9990) =     29.846 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.810 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.707 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.014 ms/op
Iteration   1: 4.135 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.995 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   8.262 ms/op
                 getUser·p0.999:  16.407 ms/op
                 getUser·p0.9999: 23.750 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   2: 4.151 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.812 ms/op
                 getUser·p0.50:   4.063 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  11.348 ms/op
                 getUser·p0.9999: 24.366 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   3: 4.007 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.950 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   8.274 ms/op
                 getUser·p0.999:  24.019 ms/op
                 getUser·p0.9999: 29.853 ms/op
                 getUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234246
  mean =      4.097 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 223827 
    [ 5.000,  7.500) = 7771 
    [ 7.500, 10.000) = 1520 
    [10.000, 12.500) = 667 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.812 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.774 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     28.017 ms/op
     p(99.9990) =     29.950 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.043 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 5.713 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.994 ±(99.9%) 0.018 ms/op
Iteration   1: 4.834 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.806 ms/op
                 listUser·p0.50:   4.575 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  26.472 ms/op
                 listUser·p0.9999: 29.557 ms/op
                 listUser·p1.00:   31.523 ms/op

Iteration   2: 4.895 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   5.928 ms/op
                 listUser·p0.99:   9.869 ms/op
                 listUser·p0.999:  23.319 ms/op
                 listUser·p0.9999: 30.242 ms/op
                 listUser·p1.00:   30.736 ms/op

Iteration   3: 4.747 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.912 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  16.564 ms/op
                 listUser·p0.9999: 19.235 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198801
  mean =      4.824 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 155696 
    [ 5.000,  7.500) = 38146 
    [ 7.500, 10.000) = 3531 
    [10.000, 12.500) = 806 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.806 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     21.902 ms/op
     p(99.9900) =     29.561 ms/op
     p(99.9990) =     31.490 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.972 ± 4.327  ops/ms
ClientPb.existUser                       thrpt       3   8.235 ± 3.061  ops/ms
ClientPb.getUser                         thrpt       3   7.987 ± 7.677  ops/ms
ClientPb.listUser                        thrpt       3   6.650 ± 3.614  ops/ms
ClientPb.createUser                       avgt       3   4.031 ± 0.346   ms/op
ClientPb.existUser                        avgt       3   3.776 ± 0.657   ms/op
ClientPb.getUser                          avgt       3   4.100 ± 0.293   ms/op
ClientPb.listUser                         avgt       3   4.642 ± 1.182   ms/op
ClientPb.createUser                     sample  238957   4.015 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.698           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.456           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.915           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.029           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.677           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.490           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.894           ms/op
ClientPb.existUser                      sample  246205   3.899 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.579           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.686           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.324           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.574           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.140           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.867           ms/op
ClientPb.getUser                        sample  234246   4.097 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.812           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.538           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.882           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.774           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.039           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.017           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.278           ms/op
ClientPb.listUser                       sample  198801   4.824 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.806           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.341           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.816           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.421           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.902           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.561           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.523           ms/op
