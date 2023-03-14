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
# Warmup Iteration   1: 1.848 ops/ms
# Warmup Iteration   2: 4.615 ops/ms
# Warmup Iteration   3: 6.891 ops/ms
Iteration   1: 8.206 ops/ms
Iteration   2: 8.236 ops/ms
Iteration   3: 7.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.120 ±(99.9%) 3.202 ops/ms [Average]
  (min, avg, max) = (7.919, 8.120, 8.236), stdev = 0.175
  CI (99.9%): [4.919, 11.322] (assumes normal distribution)


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
# Warmup Iteration   1: 2.302 ops/ms
# Warmup Iteration   2: 7.156 ops/ms
# Warmup Iteration   3: 8.069 ops/ms
Iteration   1: 8.541 ops/ms
Iteration   2: 8.094 ops/ms
Iteration   3: 8.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.406 ±(99.9%) 4.941 ops/ms [Average]
  (min, avg, max) = (8.094, 8.406, 8.582), stdev = 0.271
  CI (99.9%): [3.465, 13.347] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.292 ops/ms
# Warmup Iteration   2: 6.905 ops/ms
# Warmup Iteration   3: 7.867 ops/ms
Iteration   1: 8.155 ops/ms
Iteration   2: 8.103 ops/ms
Iteration   3: 8.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.206 ±(99.9%) 2.489 ops/ms [Average]
  (min, avg, max) = (8.103, 8.206, 8.361), stdev = 0.136
  CI (99.9%): [5.717, 10.695] (assumes normal distribution)


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
# Warmup Iteration   1: 2.191 ops/ms
# Warmup Iteration   2: 5.988 ops/ms
# Warmup Iteration   3: 6.703 ops/ms
Iteration   1: 7.134 ops/ms
Iteration   2: 6.844 ops/ms
Iteration   3: 7.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.997 ±(99.9%) 2.657 ops/ms [Average]
  (min, avg, max) = (6.844, 6.997, 7.134), stdev = 0.146
  CI (99.9%): [4.340, 9.654] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.423 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.560 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.009 ms/op
Iteration   1: 3.792 ±(99.9%) 0.011 ms/op
Iteration   2: 3.902 ±(99.9%) 0.006 ms/op
Iteration   3: 3.711 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.802 ±(99.9%) 1.744 ms/op [Average]
  (min, avg, max) = (3.711, 3.802, 3.902), stdev = 0.096
  CI (99.9%): [2.058, 5.546] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.346 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.008 ms/op
Iteration   1: 3.640 ±(99.9%) 0.004 ms/op
Iteration   2: 3.785 ±(99.9%) 0.006 ms/op
Iteration   3: 3.781 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.736 ±(99.9%) 1.508 ms/op [Average]
  (min, avg, max) = (3.640, 3.736, 3.785), stdev = 0.083
  CI (99.9%): [2.228, 5.244] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.606 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.334 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.781 ±(99.9%) 0.008 ms/op
Iteration   1: 3.737 ±(99.9%) 0.012 ms/op
Iteration   2: 3.928 ±(99.9%) 0.006 ms/op
Iteration   3: 3.914 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.860 ±(99.9%) 1.941 ms/op [Average]
  (min, avg, max) = (3.737, 3.860, 3.928), stdev = 0.106
  CI (99.9%): [1.919, 5.801] (assumes normal distribution)


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
# Warmup Iteration   1: 11.190 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.170 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.473 ±(99.9%) 0.011 ms/op
Iteration   1: 4.185 ±(99.9%) 0.012 ms/op
Iteration   2: 4.417 ±(99.9%) 0.008 ms/op
Iteration   3: 4.549 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.384 ±(99.9%) 3.367 ms/op [Average]
  (min, avg, max) = (4.185, 4.384, 4.549), stdev = 0.185
  CI (99.9%): [1.017, 7.750] (assumes normal distribution)


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
# Warmup Iteration   1: 11.631 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.659 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.311 ±(99.9%) 0.017 ms/op
Iteration   1: 3.975 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.769 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   7.767 ms/op
                 createUser·p0.999:  10.937 ms/op
                 createUser·p0.9999: 27.329 ms/op
                 createUser·p1.00:   27.787 ms/op

Iteration   2: 3.783 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.647 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   7.078 ms/op
                 createUser·p0.999:  25.132 ms/op
                 createUser·p0.9999: 28.067 ms/op
                 createUser·p1.00:   28.606 ms/op

Iteration   3: 3.820 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  26.149 ms/op
                 createUser·p0.9999: 31.543 ms/op
                 createUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 248732
  mean =      3.857 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 595 
    [ 2.500,  5.000) = 238271 
    [ 5.000,  7.500) = 7862 
    [ 7.500, 10.000) = 1323 
    [10.000, 12.500) = 357 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 136 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.610 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     23.986 ms/op
     p(99.9900) =     29.884 ms/op
     p(99.9990) =     32.261 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


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
# Warmup Iteration   1: 10.767 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.011 ms/op
Iteration   1: 3.749 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.544 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  24.259 ms/op
                 existUser·p0.9999: 29.343 ms/op
                 existUser·p1.00:   29.819 ms/op

Iteration   2: 3.704 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.733 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  13.889 ms/op
                 existUser·p0.9999: 32.715 ms/op
                 existUser·p1.00:   34.144 ms/op

Iteration   3: 3.725 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.679 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  27.136 ms/op
                 existUser·p0.9999: 30.409 ms/op
                 existUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 257531
  mean =      3.726 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1832 
    [ 2.500,  5.000) = 245660 
    [ 5.000,  7.500) = 8607 
    [ 7.500, 10.000) = 941 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 103 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.544 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     18.464 ms/op
     p(99.9900) =     31.556 ms/op
     p(99.9990) =     33.418 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 12.817 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.445 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.242 ±(99.9%) 0.015 ms/op
Iteration   1: 3.870 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   5.472 ms/op
                 getUser·p0.99:   7.520 ms/op
                 getUser·p0.999:  22.617 ms/op
                 getUser·p0.9999: 26.620 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   2: 3.774 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  26.051 ms/op
                 getUser·p0.9999: 31.426 ms/op
                 getUser·p1.00:   33.161 ms/op

Iteration   3: 3.875 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.303 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   7.873 ms/op
                 getUser·p0.999:  11.583 ms/op
                 getUser·p0.9999: 36.635 ms/op
                 getUser·p1.00:   36.831 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 250118
  mean =      3.839 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 977 
    [ 2.500,  5.000) = 237412 
    [ 5.000,  7.500) = 9432 
    [ 7.500, 10.000) = 1581 
    [10.000, 12.500) = 317 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.008 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     22.278 ms/op
     p(99.9900) =     35.914 ms/op
     p(99.9990) =     36.766 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


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
# Warmup Iteration   1: 14.597 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 5.545 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.597 ±(99.9%) 0.016 ms/op
Iteration   1: 4.574 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   4.284 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  26.699 ms/op
                 listUser·p0.9999: 37.945 ms/op
                 listUser·p1.00:   38.601 ms/op

Iteration   2: 4.577 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.753 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  18.303 ms/op
                 listUser·p0.9999: 22.250 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   3: 4.563 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.491 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  16.588 ms/op
                 listUser·p0.9999: 19.527 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209983
  mean =      4.571 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 180705 
    [ 5.000,  7.500) = 24668 
    [ 7.500, 10.000) = 3633 
    [10.000, 12.500) = 376 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.753 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     36.307 ms/op
     p(99.9990) =     38.542 ms/op
     p(99.9999) =     38.601 ms/op
    p(100.0000) =     38.601 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.120 ± 3.202  ops/ms
ClientPb.existUser                       thrpt       3   8.406 ± 4.941  ops/ms
ClientPb.getUser                         thrpt       3   8.206 ± 2.489  ops/ms
ClientPb.listUser                        thrpt       3   6.997 ± 2.657  ops/ms
ClientPb.createUser                       avgt       3   3.802 ± 1.744   ms/op
ClientPb.existUser                        avgt       3   3.736 ± 1.508   ms/op
ClientPb.getUser                          avgt       3   3.860 ± 1.941   ms/op
ClientPb.listUser                         avgt       3   4.384 ± 3.367   ms/op
ClientPb.createUser                     sample  248732   3.857 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.610           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.825           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.012           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.986           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.884           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.899           ms/op
ClientPb.existUser                      sample  257531   3.726 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.544           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.100           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.678           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.464           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.556           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.144           ms/op
ClientPb.getUser                        sample  250118   3.839 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.008           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.686           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.350           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.899           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.278           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.914           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.831           ms/op
ClientPb.listUser                       sample  209983   4.571 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.753           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.169           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.767           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.120           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.307           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.601           ms/op
