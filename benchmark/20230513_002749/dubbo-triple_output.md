# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.588 ops/ms
# Warmup Iteration   2: 3.706 ops/ms
# Warmup Iteration   3: 7.425 ops/ms
Iteration   1: 7.338 ops/ms
Iteration   2: 8.288 ops/ms
Iteration   3: 8.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.926 ±(99.9%) 9.374 ops/ms [Average]
  (min, avg, max) = (7.338, 7.926, 8.288), stdev = 0.514
  CI (99.9%): [≈ 0, 17.300] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.446 ops/ms
# Warmup Iteration   2: 6.655 ops/ms
# Warmup Iteration   3: 7.645 ops/ms
Iteration   1: 8.079 ops/ms
Iteration   2: 8.439 ops/ms
Iteration   3: 8.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.244 ±(99.9%) 3.324 ops/ms [Average]
  (min, avg, max) = (8.079, 8.244, 8.439), stdev = 0.182
  CI (99.9%): [4.920, 11.568] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.403 ops/ms
# Warmup Iteration   2: 7.248 ops/ms
# Warmup Iteration   3: 7.758 ops/ms
Iteration   1: 8.020 ops/ms
Iteration   2: 8.121 ops/ms
Iteration   3: 8.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.150 ±(99.9%) 2.693 ops/ms [Average]
  (min, avg, max) = (8.020, 8.150, 8.311), stdev = 0.148
  CI (99.9%): [5.457, 10.844] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.128 ops/ms
# Warmup Iteration   2: 5.744 ops/ms
# Warmup Iteration   3: 6.723 ops/ms
Iteration   1: 6.726 ops/ms
Iteration   2: 6.843 ops/ms
Iteration   3: 6.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.837 ±(99.9%) 1.963 ops/ms [Average]
  (min, avg, max) = (6.726, 6.837, 6.941), stdev = 0.108
  CI (99.9%): [4.874, 8.800] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.192 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.318 ±(99.9%) 0.010 ms/op
Iteration   1: 4.083 ±(99.9%) 0.010 ms/op
Iteration   2: 4.027 ±(99.9%) 0.008 ms/op
Iteration   3: 3.796 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.969 ±(99.9%) 2.779 ms/op [Average]
  (min, avg, max) = (3.796, 3.969, 4.083), stdev = 0.152
  CI (99.9%): [1.190, 6.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.465 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.005 ms/op
Iteration   1: 3.929 ±(99.9%) 0.007 ms/op
Iteration   2: 3.774 ±(99.9%) 0.005 ms/op
Iteration   3: 3.910 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.871 ±(99.9%) 1.543 ms/op [Average]
  (min, avg, max) = (3.774, 3.871, 3.929), stdev = 0.085
  CI (99.9%): [2.328, 5.414] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.781 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.354 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.003 ms/op
Iteration   1: 3.980 ±(99.9%) 0.007 ms/op
Iteration   2: 3.837 ±(99.9%) 0.012 ms/op
Iteration   3: 3.968 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.929 ±(99.9%) 1.446 ms/op [Average]
  (min, avg, max) = (3.837, 3.929, 3.980), stdev = 0.079
  CI (99.9%): [2.482, 5.375] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.074 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.808 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.612 ±(99.9%) 0.013 ms/op
Iteration   1: 4.575 ±(99.9%) 0.012 ms/op
Iteration   2: 4.569 ±(99.9%) 0.011 ms/op
Iteration   3: 4.666 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.603 ±(99.9%) 0.991 ms/op [Average]
  (min, avg, max) = (4.569, 4.603, 4.666), stdev = 0.054
  CI (99.9%): [3.612, 5.594] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.661 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 4.784 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.353 ±(99.9%) 0.018 ms/op
Iteration   1: 3.796 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   2.028 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   6.802 ms/op
                 createUser·p0.999:  11.802 ms/op
                 createUser·p0.9999: 28.887 ms/op
                 createUser·p1.00:   29.164 ms/op

Iteration   2: 3.822 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  25.428 ms/op
                 createUser·p0.9999: 29.360 ms/op
                 createUser·p1.00:   30.441 ms/op

Iteration   3: 3.845 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  26.661 ms/op
                 createUser·p0.9999: 31.535 ms/op
                 createUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 251213
  mean =      3.821 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 393 
    [ 2.500,  5.000) = 243406 
    [ 5.000,  7.500) = 6126 
    [ 7.500, 10.000) = 815 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 113 
    [27.500, 30.000) = 98 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     24.412 ms/op
     p(99.9900) =     30.422 ms/op
     p(99.9990) =     32.194 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 11.648 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.264 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.010 ms/op
Iteration   1: 3.800 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.851 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   5.292 ms/op
                 existUser·p0.99:   7.198 ms/op
                 existUser·p0.999:  22.147 ms/op
                 existUser·p0.9999: 25.480 ms/op
                 existUser·p1.00:   26.477 ms/op

Iteration   2: 3.747 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.333 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  16.555 ms/op
                 existUser·p0.9999: 28.490 ms/op
                 existUser·p1.00:   31.130 ms/op

Iteration   3: 3.843 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.991 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   7.995 ms/op
                 existUser·p0.999:  25.451 ms/op
                 existUser·p0.9999: 27.908 ms/op
                 existUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252664
  mean =      3.796 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 139 
    [ 2.500,  5.000) = 241230 
    [ 5.000,  7.500) = 9023 
    [ 7.500, 10.000) = 1646 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 126 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     21.267 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     29.391 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.186 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 4.635 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.014 ms/op
Iteration   1: 3.945 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   7.225 ms/op
                 getUser·p0.999:  23.495 ms/op
                 getUser·p0.9999: 29.376 ms/op
                 getUser·p1.00:   31.195 ms/op

Iteration   2: 3.940 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.212 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   7.315 ms/op
                 getUser·p0.999:  24.508 ms/op
                 getUser·p0.9999: 27.089 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 3.863 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.487 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.362 ms/op
                 getUser·p0.999:  10.578 ms/op
                 getUser·p0.9999: 29.989 ms/op
                 getUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 244857
  mean =      3.916 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 235037 
    [ 5.000,  7.500) = 7948 
    [ 7.500, 10.000) = 1210 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.487 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     23.396 ms/op
     p(99.9900) =     29.229 ms/op
     p(99.9990) =     30.593 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.651 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 5.486 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.851 ±(99.9%) 0.016 ms/op
Iteration   1: 4.696 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.774 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   8.583 ms/op
                 listUser·p0.999:  23.258 ms/op
                 listUser·p0.9999: 28.186 ms/op
                 listUser·p1.00:   28.803 ms/op

Iteration   2: 4.840 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  17.977 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   3: 5.095 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.789 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.259 ms/op
                 listUser·p0.95:   8.135 ms/op
                 listUser·p0.99:   10.567 ms/op
                 listUser·p0.999:  18.697 ms/op
                 listUser·p0.9999: 22.631 ms/op
                 listUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197111
  mean =      4.871 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 151792 
    [ 5.000,  7.500) = 38016 
    [ 7.500, 10.000) = 5659 
    [10.000, 12.500) = 981 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.774 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      5.587 ms/op
     p(95.0000) =      6.676 ms/op
     p(99.0000) =      9.601 ms/op
     p(99.9000) =     21.103 ms/op
     p(99.9900) =     26.702 ms/op
     p(99.9990) =     28.612 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.926 ± 9.374  ops/ms
ClientPb.existUser                       thrpt       3   8.244 ± 3.324  ops/ms
ClientPb.getUser                         thrpt       3   8.150 ± 2.693  ops/ms
ClientPb.listUser                        thrpt       3   6.837 ± 1.963  ops/ms
ClientPb.createUser                       avgt       3   3.969 ± 2.779   ms/op
ClientPb.existUser                        avgt       3   3.871 ± 1.543   ms/op
ClientPb.getUser                          avgt       3   3.929 ± 1.446   ms/op
ClientPb.listUser                         avgt       3   4.603 ± 0.991   ms/op
ClientPb.createUser                     sample  251213   3.821 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.315           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.588           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.537           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.412           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.422           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.571           ms/op
ClientPb.existUser                      sample  252664   3.796 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.333           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.071           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.719           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.307           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.267           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.886           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.130           ms/op
ClientPb.getUser                        sample  244857   3.916 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.487           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.784           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.922           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.396           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.229           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.195           ms/op
ClientPb.listUser                       sample  197111   4.871 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.774           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.676           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.601           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.103           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.702           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.803           ms/op
