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
# Warmup Iteration   1: 1.881 ops/ms
# Warmup Iteration   2: 4.773 ops/ms
# Warmup Iteration   3: 7.982 ops/ms
Iteration   1: 8.621 ops/ms
Iteration   2: 8.848 ops/ms
Iteration   3: 8.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.724 ±(99.9%) 2.100 ops/ms [Average]
  (min, avg, max) = (8.621, 8.724, 8.848), stdev = 0.115
  CI (99.9%): [6.624, 10.823] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.685 ops/ms
# Warmup Iteration   2: 8.347 ops/ms
# Warmup Iteration   3: 8.806 ops/ms
Iteration   1: 9.024 ops/ms
Iteration   2: 9.036 ops/ms
Iteration   3: 8.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.753 ±(99.9%) 8.754 ops/ms [Average]
  (min, avg, max) = (8.199, 8.753, 9.036), stdev = 0.480
  CI (99.9%): [≈ 0, 17.507] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.653 ops/ms
# Warmup Iteration   2: 7.333 ops/ms
# Warmup Iteration   3: 8.841 ops/ms
Iteration   1: 8.819 ops/ms
Iteration   2: 8.479 ops/ms
Iteration   3: 8.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.665 ±(99.9%) 3.144 ops/ms [Average]
  (min, avg, max) = (8.479, 8.665, 8.819), stdev = 0.172
  CI (99.9%): [5.521, 11.809] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.723 ops/ms
# Warmup Iteration   2: 6.466 ops/ms
# Warmup Iteration   3: 7.079 ops/ms
Iteration   1: 7.109 ops/ms
Iteration   2: 7.443 ops/ms
Iteration   3: 7.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.343 ±(99.9%) 3.719 ops/ms [Average]
  (min, avg, max) = (7.109, 7.343, 7.479), stdev = 0.204
  CI (99.9%): [3.624, 11.063] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.835 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.310 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.010 ms/op
Iteration   1: 4.098 ±(99.9%) 0.003 ms/op
Iteration   2: 3.871 ±(99.9%) 0.013 ms/op
Iteration   3: 3.795 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.921 ±(99.9%) 2.878 ms/op [Average]
  (min, avg, max) = (3.795, 3.921, 4.098), stdev = 0.158
  CI (99.9%): [1.044, 6.799] (assumes normal distribution)


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
# Warmup Iteration   1: 12.409 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.360 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.008 ms/op
Iteration   1: 3.791 ±(99.9%) 0.013 ms/op
Iteration   2: 3.699 ±(99.9%) 0.006 ms/op
Iteration   3: 3.657 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.715 ±(99.9%) 1.246 ms/op [Average]
  (min, avg, max) = (3.657, 3.715, 3.791), stdev = 0.068
  CI (99.9%): [2.469, 4.962] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.005 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.804 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.004 ms/op
Iteration   1: 3.998 ±(99.9%) 0.007 ms/op
Iteration   2: 3.891 ±(99.9%) 0.010 ms/op
Iteration   3: 3.928 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.939 ±(99.9%) 0.991 ms/op [Average]
  (min, avg, max) = (3.891, 3.939, 3.998), stdev = 0.054
  CI (99.9%): [2.948, 4.930] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.290 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.361 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.310 ±(99.9%) 0.012 ms/op
Iteration   1: 4.336 ±(99.9%) 0.012 ms/op
Iteration   2: 4.291 ±(99.9%) 0.009 ms/op
Iteration   3: 4.235 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.287 ±(99.9%) 0.927 ms/op [Average]
  (min, avg, max) = (4.235, 4.287, 4.336), stdev = 0.051
  CI (99.9%): [3.360, 5.215] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.043 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 5.260 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.501 ±(99.9%) 0.019 ms/op
Iteration   1: 4.130 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.874 ms/op
                 createUser·p0.95:   5.628 ms/op
                 createUser·p0.99:   8.249 ms/op
                 createUser·p0.999:  24.510 ms/op
                 createUser·p0.9999: 29.391 ms/op
                 createUser·p1.00:   30.966 ms/op

Iteration   2: 4.038 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.612 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   4.940 ms/op
                 createUser·p0.99:   6.588 ms/op
                 createUser·p0.999:  26.355 ms/op
                 createUser·p0.9999: 37.426 ms/op
                 createUser·p1.00:   38.601 ms/op

Iteration   3: 3.842 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.204 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.496 ms/op
                 createUser·p0.999:  26.179 ms/op
                 createUser·p0.9999: 31.162 ms/op
                 createUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239998
  mean =      4.000 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 283 
    [ 2.500,  5.000) = 227898 
    [ 5.000,  7.500) = 9557 
    [ 7.500, 10.000) = 1538 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 104 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      7.316 ms/op
     p(99.9000) =     25.264 ms/op
     p(99.9900) =     36.766 ms/op
     p(99.9990) =     38.076 ms/op
     p(99.9999) =     38.601 ms/op
    p(100.0000) =     38.601 ms/op


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
# Warmup Iteration   1: 10.620 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 5.185 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.011 ms/op
Iteration   1: 3.730 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.612 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   3.985 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   6.259 ms/op
                 existUser·p0.999:  22.716 ms/op
                 existUser·p0.9999: 25.573 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   2: 3.817 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.876 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  13.976 ms/op
                 existUser·p0.9999: 27.513 ms/op
                 existUser·p1.00:   29.393 ms/op

Iteration   3: 3.957 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.176 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   7.601 ms/op
                 existUser·p0.999:  17.433 ms/op
                 existUser·p0.9999: 30.373 ms/op
                 existUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250366
  mean =      3.833 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 340 
    [ 2.500,  5.000) = 240679 
    [ 5.000,  7.500) = 7606 
    [ 7.500, 10.000) = 1072 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.827 ms/op
     p(99.9000) =     17.126 ms/op
     p(99.9900) =     29.358 ms/op
     p(99.9990) =     31.670 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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
# Warmup Iteration   1: 13.369 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.752 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.012 ms/op
Iteration   1: 3.976 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   8.184 ms/op
                 getUser·p0.999:  23.413 ms/op
                 getUser·p0.9999: 30.107 ms/op
                 getUser·p1.00:   31.588 ms/op

Iteration   2: 4.035 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.909 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  20.709 ms/op
                 getUser·p0.9999: 29.330 ms/op
                 getUser·p1.00:   31.719 ms/op

Iteration   3: 4.072 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.485 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.874 ms/op
                 getUser·p0.95:   5.816 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  26.984 ms/op
                 getUser·p0.9999: 32.740 ms/op
                 getUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238269
  mean =      4.027 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 171 
    [ 2.500,  5.000) = 222593 
    [ 5.000,  7.500) = 12800 
    [ 7.500, 10.000) = 2056 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.485 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     23.542 ms/op
     p(99.9900) =     31.507 ms/op
     p(99.9990) =     32.932 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


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
# Warmup Iteration   1: 14.420 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 5.365 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.551 ±(99.9%) 0.014 ms/op
Iteration   1: 4.691 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  26.507 ms/op
                 listUser·p0.9999: 31.896 ms/op
                 listUser·p1.00:   32.473 ms/op

Iteration   2: 4.652 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 20.693 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   3: 4.613 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   8.839 ms/op
                 listUser·p0.999:  17.211 ms/op
                 listUser·p0.9999: 19.303 ms/op
                 listUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 206088
  mean =      4.652 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 179978 
    [ 5.000,  7.500) = 20733 
    [ 7.500, 10.000) = 3967 
    [10.000, 12.500) = 789 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      9.241 ms/op
     p(99.9000) =     19.104 ms/op
     p(99.9900) =     31.175 ms/op
     p(99.9990) =     32.398 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.724 ± 2.100  ops/ms
ClientPb.existUser                       thrpt       3   8.753 ± 8.754  ops/ms
ClientPb.getUser                         thrpt       3   8.665 ± 3.144  ops/ms
ClientPb.listUser                        thrpt       3   7.343 ± 3.719  ops/ms
ClientPb.createUser                       avgt       3   3.921 ± 2.878   ms/op
ClientPb.existUser                        avgt       3   3.715 ± 1.246   ms/op
ClientPb.getUser                          avgt       3   3.939 ± 0.991   ms/op
ClientPb.listUser                         avgt       3   4.287 ± 0.927   ms/op
ClientPb.createUser                     sample  239998   4.000 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.046           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.989           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.316           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.264           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.766           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.601           ms/op
ClientPb.existUser                      sample  250366   3.833 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.176           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.702           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.827           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.126           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.358           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.719           ms/op
ClientPb.getUser                        sample  238269   4.027 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.485           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.669           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.635           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.542           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.507           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.096           ms/op
ClientPb.listUser                       sample  206088   4.652 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.638           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.095           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.241           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.104           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.175           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.473           ms/op
