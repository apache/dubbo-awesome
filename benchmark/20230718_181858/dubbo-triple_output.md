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
# Warmup Iteration   1: 1.635 ops/ms
# Warmup Iteration   2: 3.350 ops/ms
# Warmup Iteration   3: 7.147 ops/ms
Iteration   1: 7.566 ops/ms
Iteration   2: 7.754 ops/ms
Iteration   3: 8.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.807 ±(99.9%) 4.941 ops/ms [Average]
  (min, avg, max) = (7.566, 7.807, 8.100), stdev = 0.271
  CI (99.9%): [2.866, 12.747] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.529 ops/ms
# Warmup Iteration   2: 6.795 ops/ms
# Warmup Iteration   3: 8.008 ops/ms
Iteration   1: 8.289 ops/ms
Iteration   2: 8.671 ops/ms
Iteration   3: 8.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.332 ±(99.9%) 5.833 ops/ms [Average]
  (min, avg, max) = (8.036, 8.332, 8.671), stdev = 0.320
  CI (99.9%): [2.500, 14.165] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.178 ops/ms
# Warmup Iteration   2: 6.728 ops/ms
# Warmup Iteration   3: 7.497 ops/ms
Iteration   1: 7.990 ops/ms
Iteration   2: 8.269 ops/ms
Iteration   3: 7.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.052 ±(99.9%) 3.520 ops/ms [Average]
  (min, avg, max) = (7.898, 8.052, 8.269), stdev = 0.193
  CI (99.9%): [4.532, 11.573] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.203 ops/ms
# Warmup Iteration   2: 5.527 ops/ms
# Warmup Iteration   3: 6.553 ops/ms
Iteration   1: 6.705 ops/ms
Iteration   2: 6.924 ops/ms
Iteration   3: 6.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.779 ±(99.9%) 2.297 ops/ms [Average]
  (min, avg, max) = (6.705, 6.779, 6.924), stdev = 0.126
  CI (99.9%): [4.482, 9.076] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 13.006 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.608 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.398 ±(99.9%) 0.011 ms/op
Iteration   1: 4.306 ±(99.9%) 0.007 ms/op
Iteration   2: 4.068 ±(99.9%) 0.007 ms/op
Iteration   3: 4.052 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.142 ±(99.9%) 2.592 ms/op [Average]
  (min, avg, max) = (4.052, 4.142, 4.306), stdev = 0.142
  CI (99.9%): [1.550, 6.734] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.747 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.005 ms/op
Iteration   1: 3.711 ±(99.9%) 0.008 ms/op
Iteration   2: 3.914 ±(99.9%) 0.008 ms/op
Iteration   3: 3.675 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.767 ±(99.9%) 2.356 ms/op [Average]
  (min, avg, max) = (3.675, 3.767, 3.914), stdev = 0.129
  CI (99.9%): [1.411, 6.123] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.764 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.474 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.004 ms/op
Iteration   1: 4.059 ±(99.9%) 0.005 ms/op
Iteration   2: 4.014 ±(99.9%) 0.007 ms/op
Iteration   3: 3.925 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.999 ±(99.9%) 1.239 ms/op [Average]
  (min, avg, max) = (3.925, 3.999, 4.059), stdev = 0.068
  CI (99.9%): [2.761, 5.238] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.877 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.469 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.656 ±(99.9%) 0.008 ms/op
Iteration   1: 4.707 ±(99.9%) 0.010 ms/op
Iteration   2: 4.683 ±(99.9%) 0.006 ms/op
Iteration   3: 4.317 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.569 ±(99.9%) 3.988 ms/op [Average]
  (min, avg, max) = (4.317, 4.569, 4.707), stdev = 0.219
  CI (99.9%): [0.581, 8.557] (assumes normal distribution)


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
# Warmup Iteration   1: 14.978 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 5.313 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.256 ±(99.9%) 0.017 ms/op
Iteration   1: 4.036 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.851 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.276 ms/op
                 createUser·p0.99:   7.823 ms/op
                 createUser·p0.999:  22.340 ms/op
                 createUser·p0.9999: 25.201 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   2: 3.941 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.701 ms/op
                 createUser·p0.999:  24.407 ms/op
                 createUser·p0.9999: 26.928 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   3: 3.922 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.784 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  16.753 ms/op
                 createUser·p0.9999: 29.088 ms/op
                 createUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241841
  mean =      3.966 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 203 
    [ 2.500,  5.000) = 230337 
    [ 5.000,  7.500) = 9504 
    [ 7.500, 10.000) = 1098 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 92 

  Percentiles, ms/op:
      p(0.0000) =      1.686 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     22.255 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     29.346 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.617 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.495 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.415 ±(99.9%) 0.017 ms/op
Iteration   1: 3.873 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   5.120 ms/op
                 existUser·p0.99:   7.389 ms/op
                 existUser·p0.999:  10.797 ms/op
                 existUser·p0.9999: 26.230 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   2: 3.860 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.477 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   7.234 ms/op
                 existUser·p0.999:  24.957 ms/op
                 existUser·p0.9999: 27.783 ms/op
                 existUser·p1.00:   28.541 ms/op

Iteration   3: 3.758 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  10.746 ms/op
                 existUser·p0.9999: 31.670 ms/op
                 existUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250505
  mean =      3.830 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 272 
    [ 2.500,  5.000) = 238684 
    [ 5.000,  7.500) = 9696 
    [ 7.500, 10.000) = 1349 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 112 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     14.614 ms/op
     p(99.9900) =     29.817 ms/op
     p(99.9990) =     32.161 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 11.654 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 5.180 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.414 ±(99.9%) 0.017 ms/op
Iteration   1: 4.019 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.495 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   8.733 ms/op
                 getUser·p0.999:  20.195 ms/op
                 getUser·p0.9999: 25.298 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   2: 3.949 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.913 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.629 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  22.611 ms/op
                 getUser·p0.9999: 26.306 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   3: 3.893 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.085 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  11.984 ms/op
                 getUser·p0.9999: 27.682 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 242752
  mean =      3.953 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 234339 
    [ 5.000,  7.500) = 6136 
    [ 7.500, 10.000) = 1398 
    [10.000, 12.500) = 462 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 89 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     20.037 ms/op
     p(99.9900) =     26.697 ms/op
     p(99.9990) =     28.457 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 13.896 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 5.728 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.046 ±(99.9%) 0.021 ms/op
Iteration   1: 4.709 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.511 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  26.181 ms/op
                 listUser·p0.9999: 30.068 ms/op
                 listUser·p1.00:   31.916 ms/op

Iteration   2: 4.672 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  18.678 ms/op
                 listUser·p0.9999: 23.263 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   3: 4.692 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   8.323 ms/op
                 listUser·p0.999:  17.226 ms/op
                 listUser·p0.9999: 18.913 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204584
  mean =      4.691 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 175174 
    [ 5.000,  7.500) = 25663 
    [ 7.500, 10.000) = 2771 
    [10.000, 12.500) = 374 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.511 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     18.691 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     31.573 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.807 ± 4.941  ops/ms
ClientPb.existUser                       thrpt       3   8.332 ± 5.833  ops/ms
ClientPb.getUser                         thrpt       3   8.052 ± 3.520  ops/ms
ClientPb.listUser                        thrpt       3   6.779 ± 2.297  ops/ms
ClientPb.createUser                       avgt       3   4.142 ± 2.592   ms/op
ClientPb.existUser                        avgt       3   3.767 ± 2.356   ms/op
ClientPb.getUser                          avgt       3   3.999 ± 1.239   ms/op
ClientPb.listUser                         avgt       3   4.569 ± 3.988   ms/op
ClientPb.createUser                     sample  241841   3.966 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.686           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.940           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.963           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.255           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.213           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.655           ms/op
ClientPb.existUser                      sample  250505   3.830 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.438           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.866           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.184           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.614           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.817           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.309           ms/op
ClientPb.getUser                        sample  242752   3.953 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.495           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.661           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.315           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.037           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.697           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.574           ms/op
ClientPb.listUser                       sample  204584   4.691 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.511           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.161           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.691           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.213           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.916           ms/op
