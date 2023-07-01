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
# Warmup Iteration   1: 1.896 ops/ms
# Warmup Iteration   2: 5.395 ops/ms
# Warmup Iteration   3: 8.084 ops/ms
Iteration   1: 8.824 ops/ms
Iteration   2: 9.191 ops/ms
Iteration   3: 8.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.997 ±(99.9%) 3.356 ops/ms [Average]
  (min, avg, max) = (8.824, 8.997, 9.191), stdev = 0.184
  CI (99.9%): [5.641, 12.354] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.562 ops/ms
# Warmup Iteration   2: 8.326 ops/ms
# Warmup Iteration   3: 8.795 ops/ms
Iteration   1: 9.696 ops/ms
Iteration   2: 9.479 ops/ms
Iteration   3: 9.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.677 ±(99.9%) 3.445 ops/ms [Average]
  (min, avg, max) = (9.479, 9.677, 9.855), stdev = 0.189
  CI (99.9%): [6.232, 13.122] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.511 ops/ms
# Warmup Iteration   2: 8.288 ops/ms
# Warmup Iteration   3: 8.769 ops/ms
Iteration   1: 9.061 ops/ms
Iteration   2: 9.246 ops/ms
Iteration   3: 9.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.107 ±(99.9%) 2.234 ops/ms [Average]
  (min, avg, max) = (9.015, 9.107, 9.246), stdev = 0.122
  CI (99.9%): [6.873, 11.341] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.258 ops/ms
# Warmup Iteration   2: 5.591 ops/ms
# Warmup Iteration   3: 7.289 ops/ms
Iteration   1: 7.095 ops/ms
Iteration   2: 7.555 ops/ms
Iteration   3: 7.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.412 ±(99.9%) 5.017 ops/ms [Average]
  (min, avg, max) = (7.095, 7.412, 7.586), stdev = 0.275
  CI (99.9%): [2.395, 12.429] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.064 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.207 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.705 ±(99.9%) 0.010 ms/op
Iteration   1: 3.690 ±(99.9%) 0.005 ms/op
Iteration   2: 3.643 ±(99.9%) 0.010 ms/op
Iteration   3: 3.558 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.630 ±(99.9%) 1.221 ms/op [Average]
  (min, avg, max) = (3.558, 3.630, 3.690), stdev = 0.067
  CI (99.9%): [2.409, 4.851] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 10.411 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.831 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.006 ms/op
Iteration   1: 3.401 ±(99.9%) 0.003 ms/op
Iteration   2: 3.415 ±(99.9%) 0.004 ms/op
Iteration   3: 3.520 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.445 ±(99.9%) 1.183 ms/op [Average]
  (min, avg, max) = (3.401, 3.445, 3.520), stdev = 0.065
  CI (99.9%): [2.262, 4.628] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 10.809 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.774 ±(99.9%) 0.007 ms/op
Iteration   1: 3.763 ±(99.9%) 0.004 ms/op
Iteration   2: 3.554 ±(99.9%) 0.005 ms/op
Iteration   3: 3.695 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.671 ±(99.9%) 1.945 ms/op [Average]
  (min, avg, max) = (3.554, 3.671, 3.763), stdev = 0.107
  CI (99.9%): [1.726, 5.615] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 13.387 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.909 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.413 ±(99.9%) 0.009 ms/op
Iteration   1: 4.323 ±(99.9%) 0.006 ms/op
Iteration   2: 4.159 ±(99.9%) 0.015 ms/op
Iteration   3: 4.014 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.166 ±(99.9%) 2.820 ms/op [Average]
  (min, avg, max) = (4.014, 4.166, 4.323), stdev = 0.155
  CI (99.9%): [1.346, 6.985] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.233 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.539 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.764 ±(99.9%) 0.011 ms/op
Iteration   1: 3.915 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.456 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   6.750 ms/op
                 createUser·p0.99:   8.028 ms/op
                 createUser·p0.999:  22.533 ms/op
                 createUser·p0.9999: 25.286 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   2: 3.481 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.872 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  23.695 ms/op
                 createUser·p0.9999: 26.378 ms/op
                 createUser·p1.00:   28.279 ms/op

Iteration   3: 3.593 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   6.340 ms/op
                 createUser·p0.999:  22.413 ms/op
                 createUser·p0.9999: 29.786 ms/op
                 createUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 262566
  mean =      3.654 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3606 
    [ 2.500,  5.000) = 246765 
    [ 5.000,  7.500) = 8778 
    [ 7.500, 10.000) = 2919 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     22.512 ms/op
     p(99.9900) =     28.836 ms/op
     p(99.9990) =     30.704 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.268 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.826 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.010 ms/op
Iteration   1: 3.400 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.100 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  20.313 ms/op
                 existUser·p0.9999: 22.386 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   2: 3.407 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.831 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   6.163 ms/op
                 existUser·p0.999:  20.812 ms/op
                 existUser·p0.9999: 23.535 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   3: 3.396 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  12.222 ms/op
                 existUser·p0.9999: 31.075 ms/op
                 existUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282182
  mean =      3.401 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9255 
    [ 2.500,  5.000) = 265835 
    [ 5.000,  7.500) = 5886 
    [ 7.500, 10.000) = 705 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     14.218 ms/op
     p(99.9900) =     29.707 ms/op
     p(99.9990) =     31.481 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.233 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.658 ±(99.9%) 0.014 ms/op
Iteration   1: 3.745 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.612 ms/op
                 getUser·p0.50:   3.518 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   5.636 ms/op
                 getUser·p0.99:   8.061 ms/op
                 getUser·p0.999:  23.545 ms/op
                 getUser·p0.9999: 26.000 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   2: 3.588 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.401 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  24.898 ms/op
                 getUser·p0.9999: 27.793 ms/op
                 getUser·p1.00:   29.393 ms/op

Iteration   3: 3.593 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   4.780 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  9.617 ms/op
                 getUser·p0.9999: 32.444 ms/op
                 getUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 263630
  mean =      3.640 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4030 
    [ 2.500,  5.000) = 247286 
    [ 5.000,  7.500) = 10187 
    [ 7.500, 10.000) = 1582 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 127 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     15.883 ms/op
     p(99.9900) =     31.544 ms/op
     p(99.9990) =     32.631 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.773 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.785 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.551 ±(99.9%) 0.016 ms/op
Iteration   1: 4.240 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.968 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.904 ms/op
                 listUser·p0.999:  24.156 ms/op
                 listUser·p0.9999: 30.005 ms/op
                 listUser·p1.00:   30.605 ms/op

Iteration   2: 4.196 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.791 ms/op
                 listUser·p0.999:  16.630 ms/op
                 listUser·p0.9999: 24.609 ms/op
                 listUser·p1.00:   28.377 ms/op

Iteration   3: 4.344 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 20.611 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 225304
  mean =      4.259 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 211732 
    [ 5.000,  7.500) = 10217 
    [ 7.500, 10.000) = 2201 
    [10.000, 12.500) = 431 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.968 ms/op
     p(50.0000) =      4.051 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      7.946 ms/op
     p(99.9000) =     19.346 ms/op
     p(99.9900) =     28.500 ms/op
     p(99.9990) =     30.474 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.997 ± 3.356  ops/ms
ClientPb.existUser                       thrpt       3   9.677 ± 3.445  ops/ms
ClientPb.getUser                         thrpt       3   9.107 ± 2.234  ops/ms
ClientPb.listUser                        thrpt       3   7.412 ± 5.017  ops/ms
ClientPb.createUser                       avgt       3   3.630 ± 1.221   ms/op
ClientPb.existUser                        avgt       3   3.445 ± 1.183   ms/op
ClientPb.getUser                          avgt       3   3.671 ± 1.945   ms/op
ClientPb.listUser                         avgt       3   4.166 ± 2.820   ms/op
ClientPb.createUser                     sample  262566   3.654 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.456           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.457           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.850           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.668           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.512           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.836           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.736           ms/op
ClientPb.existUser                      sample  282182   3.401 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.726           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.046           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.218           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.707           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.687           ms/op
ClientPb.getUser                        sample  263630   3.640 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.319           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.457           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.907           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.168           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.883           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.544           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.735           ms/op
ClientPb.listUser                       sample  225304   4.259 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.968           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.051           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.136           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.946           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.346           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.500           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.605           ms/op
