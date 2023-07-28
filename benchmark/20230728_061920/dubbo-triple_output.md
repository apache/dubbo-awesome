# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.927 ops/ms
# Warmup Iteration   2: 5.193 ops/ms
# Warmup Iteration   3: 8.042 ops/ms
Iteration   1: 8.011 ops/ms
Iteration   2: 8.519 ops/ms
Iteration   3: 8.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.375 ±(99.9%) 5.797 ops/ms [Average]
  (min, avg, max) = (8.011, 8.375, 8.595), stdev = 0.318
  CI (99.9%): [2.577, 14.172] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.390 ops/ms
# Warmup Iteration   2: 7.270 ops/ms
# Warmup Iteration   3: 9.079 ops/ms
Iteration   1: 8.944 ops/ms
Iteration   2: 9.155 ops/ms
Iteration   3: 8.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.978 ±(99.9%) 2.959 ops/ms [Average]
  (min, avg, max) = (8.836, 8.978, 9.155), stdev = 0.162
  CI (99.9%): [6.019, 11.937] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.353 ops/ms
# Warmup Iteration   2: 7.510 ops/ms
# Warmup Iteration   3: 8.594 ops/ms
Iteration   1: 8.695 ops/ms
Iteration   2: 8.697 ops/ms
Iteration   3: 8.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.795 ±(99.9%) 3.114 ops/ms [Average]
  (min, avg, max) = (8.695, 8.795, 8.992), stdev = 0.171
  CI (99.9%): [5.680, 11.909] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.339 ops/ms
# Warmup Iteration   2: 6.496 ops/ms
# Warmup Iteration   3: 6.707 ops/ms
Iteration   1: 7.167 ops/ms
Iteration   2: 7.516 ops/ms
Iteration   3: 7.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.241 ±(99.9%) 4.498 ops/ms [Average]
  (min, avg, max) = (7.040, 7.241, 7.516), stdev = 0.247
  CI (99.9%): [2.743, 11.739] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 11.727 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.195 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.717 ±(99.9%) 0.007 ms/op
Iteration   1: 3.817 ±(99.9%) 0.005 ms/op
Iteration   2: 3.818 ±(99.9%) 0.009 ms/op
Iteration   3: 3.565 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.733 ±(99.9%) 2.656 ms/op [Average]
  (min, avg, max) = (3.565, 3.733, 3.818), stdev = 0.146
  CI (99.9%): [1.078, 6.389] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.587 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.372 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.005 ms/op
Iteration   1: 3.415 ±(99.9%) 0.005 ms/op
Iteration   2: 3.625 ±(99.9%) 0.004 ms/op
Iteration   3: 3.650 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.563 ±(99.9%) 2.361 ms/op [Average]
  (min, avg, max) = (3.415, 3.563, 3.650), stdev = 0.129
  CI (99.9%): [1.203, 5.924] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.427 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.005 ms/op
Iteration   1: 3.742 ±(99.9%) 0.005 ms/op
Iteration   2: 3.799 ±(99.9%) 0.005 ms/op
Iteration   3: 3.587 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.710 ±(99.9%) 1.998 ms/op [Average]
  (min, avg, max) = (3.587, 3.710, 3.799), stdev = 0.110
  CI (99.9%): [1.711, 5.708] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.766 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.924 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.519 ±(99.9%) 0.010 ms/op
Iteration   1: 4.538 ±(99.9%) 0.008 ms/op
Iteration   2: 4.399 ±(99.9%) 0.007 ms/op
Iteration   3: 4.243 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.393 ±(99.9%) 2.690 ms/op [Average]
  (min, avg, max) = (4.243, 4.393, 4.538), stdev = 0.147
  CI (99.9%): [1.703, 7.083] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.090 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.413 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.284 ±(99.9%) 0.017 ms/op
Iteration   1: 3.850 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   7.096 ms/op
                 createUser·p0.999:  24.109 ms/op
                 createUser·p0.9999: 27.220 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   2: 3.982 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.665 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.456 ms/op
                 createUser·p0.99:   7.520 ms/op
                 createUser·p0.999:  12.403 ms/op
                 createUser·p0.9999: 27.491 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   3: 3.896 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.947 ms/op
                 createUser·p0.999:  26.736 ms/op
                 createUser·p0.9999: 33.548 ms/op
                 createUser·p1.00:   37.487 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 245513
  mean =      3.908 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1992 
    [ 2.500,  5.000) = 229474 
    [ 5.000,  7.500) = 11787 
    [ 7.500, 10.000) = 1464 
    [10.000, 12.500) = 378 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 125 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     23.986 ms/op
     p(99.9900) =     30.209 ms/op
     p(99.9990) =     34.578 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.709 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.879 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.624 ±(99.9%) 0.011 ms/op
Iteration   1: 3.704 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.327 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   7.062 ms/op
                 existUser·p0.999:  13.135 ms/op
                 existUser·p0.9999: 23.703 ms/op
                 existUser·p1.00:   24.642 ms/op

Iteration   2: 3.486 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  19.407 ms/op
                 existUser·p0.9999: 23.822 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   3: 3.563 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.675 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.096 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   6.513 ms/op
                 existUser·p0.999:  23.744 ms/op
                 existUser·p0.9999: 26.577 ms/op
                 existUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 267767
  mean =      3.582 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7232 
    [ 2.500,  5.000) = 250899 
    [ 5.000,  7.500) = 7831 
    [ 7.500, 10.000) = 1282 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.671 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     25.836 ms/op
     p(99.9990) =     27.141 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.174 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.592 ±(99.9%) 0.012 ms/op
Iteration   1: 3.607 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.569 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   7.528 ms/op
                 getUser·p0.999:  19.988 ms/op
                 getUser·p0.9999: 23.101 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   2: 3.794 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.993 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.676 ms/op
                 getUser·p0.999:  11.201 ms/op
                 getUser·p0.9999: 29.781 ms/op
                 getUser·p1.00:   30.376 ms/op

Iteration   3: 3.838 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.731 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   7.504 ms/op
                 getUser·p0.999:  23.998 ms/op
                 getUser·p0.9999: 30.638 ms/op
                 getUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 256340
  mean =      3.744 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2222 
    [ 2.500,  5.000) = 244009 
    [ 5.000,  7.500) = 7876 
    [ 7.500, 10.000) = 1497 
    [10.000, 12.500) = 441 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     17.282 ms/op
     p(99.9900) =     29.655 ms/op
     p(99.9990) =     31.347 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.334 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.984 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.818 ±(99.9%) 0.017 ms/op
Iteration   1: 4.407 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.888 ms/op
                 listUser·p0.50:   4.227 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  22.741 ms/op
                 listUser·p0.9999: 26.443 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   2: 4.413 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   4.252 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 20.825 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   3: 4.362 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   4.219 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 22.829 ms/op
                 listUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 218214
  mean =      4.394 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 127 
    [ 2.500,  5.000) = 199167 
    [ 5.000,  7.500) = 13755 
    [ 7.500, 10.000) = 3622 
    [10.000, 12.500) = 978 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.888 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      9.107 ms/op
     p(99.9000) =     19.825 ms/op
     p(99.9900) =     25.112 ms/op
     p(99.9990) =     27.048 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.375 ± 5.797  ops/ms
ClientPb.existUser                       thrpt       3   8.978 ± 2.959  ops/ms
ClientPb.getUser                         thrpt       3   8.795 ± 3.114  ops/ms
ClientPb.listUser                        thrpt       3   7.241 ± 4.498  ops/ms
ClientPb.createUser                       avgt       3   3.733 ± 2.656   ms/op
ClientPb.existUser                        avgt       3   3.563 ± 2.361   ms/op
ClientPb.getUser                          avgt       3   3.710 ± 1.998   ms/op
ClientPb.listUser                         avgt       3   4.393 ± 2.690   ms/op
ClientPb.createUser                     sample  245513   3.908 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.341           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.571           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.161           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.266           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.986           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.209           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.487           ms/op
ClientPb.existUser                      sample  267767   3.582 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.315           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.121           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.637           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.671           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.238           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.836           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.951           ms/op
ClientPb.getUser                        sample  256340   3.744 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.569           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.735           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.135           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.282           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.655           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.556           ms/op
ClientPb.listUser                       sample  218214   4.394 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.888           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.107           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.825           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.112           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.230           ms/op
