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
# Warmup Iteration   1: 1.520 ops/ms
# Warmup Iteration   2: 3.357 ops/ms
# Warmup Iteration   3: 6.924 ops/ms
Iteration   1: 7.768 ops/ms
Iteration   2: 7.750 ops/ms
Iteration   3: 7.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.664 ±(99.9%) 3.004 ops/ms [Average]
  (min, avg, max) = (7.474, 7.664, 7.768), stdev = 0.165
  CI (99.9%): [4.660, 10.667] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.413 ops/ms
# Warmup Iteration   2: 7.261 ops/ms
# Warmup Iteration   3: 7.653 ops/ms
Iteration   1: 8.326 ops/ms
Iteration   2: 8.546 ops/ms
Iteration   3: 8.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.341 ±(99.9%) 3.611 ops/ms [Average]
  (min, avg, max) = (8.151, 8.341, 8.546), stdev = 0.198
  CI (99.9%): [4.730, 11.952] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.143 ops/ms
# Warmup Iteration   2: 6.390 ops/ms
# Warmup Iteration   3: 7.838 ops/ms
Iteration   1: 7.451 ops/ms
Iteration   2: 7.693 ops/ms
Iteration   3: 7.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.700 ±(99.9%) 4.607 ops/ms [Average]
  (min, avg, max) = (7.451, 7.700, 7.956), stdev = 0.253
  CI (99.9%): [3.093, 12.307] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.151 ops/ms
# Warmup Iteration   2: 5.781 ops/ms
# Warmup Iteration   3: 6.722 ops/ms
Iteration   1: 6.816 ops/ms
Iteration   2: 6.860 ops/ms
Iteration   3: 6.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.832 ±(99.9%) 0.436 ops/ms [Average]
  (min, avg, max) = (6.816, 6.832, 6.860), stdev = 0.024
  CI (99.9%): [6.396, 7.269] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.207 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.867 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.007 ms/op
Iteration   1: 3.831 ±(99.9%) 0.007 ms/op
Iteration   2: 3.866 ±(99.9%) 0.007 ms/op
Iteration   3: 3.963 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.887 ±(99.9%) 1.248 ms/op [Average]
  (min, avg, max) = (3.831, 3.887, 3.963), stdev = 0.068
  CI (99.9%): [2.639, 5.135] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.683 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.527 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.004 ms/op
Iteration   1: 3.860 ±(99.9%) 0.010 ms/op
Iteration   2: 3.749 ±(99.9%) 0.009 ms/op
Iteration   3: 3.877 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.829 ±(99.9%) 1.265 ms/op [Average]
  (min, avg, max) = (3.749, 3.829, 3.877), stdev = 0.069
  CI (99.9%): [2.564, 5.094] (assumes normal distribution)


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
# Warmup Iteration   1: 13.552 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.581 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.008 ms/op
Iteration   1: 3.917 ±(99.9%) 0.008 ms/op
Iteration   2: 4.105 ±(99.9%) 0.004 ms/op
Iteration   3: 3.956 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.993 ±(99.9%) 1.810 ms/op [Average]
  (min, avg, max) = (3.917, 3.993, 4.105), stdev = 0.099
  CI (99.9%): [2.183, 5.803] (assumes normal distribution)


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
# Warmup Iteration   1: 14.894 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.877 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.680 ±(99.9%) 0.015 ms/op
Iteration   1: 4.750 ±(99.9%) 0.011 ms/op
Iteration   2: 4.512 ±(99.9%) 0.019 ms/op
Iteration   3: 4.734 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.665 ±(99.9%) 2.420 ms/op [Average]
  (min, avg, max) = (4.512, 4.665, 4.750), stdev = 0.133
  CI (99.9%): [2.245, 7.086] (assumes normal distribution)


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
# Warmup Iteration   1: 13.163 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 4.943 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.392 ±(99.9%) 0.018 ms/op
Iteration   1: 4.350 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.985 ms/op
                 createUser·p0.50:   4.129 ms/op
                 createUser·p0.90:   5.112 ms/op
                 createUser·p0.95:   5.767 ms/op
                 createUser·p0.99:   8.503 ms/op
                 createUser·p0.999:  19.280 ms/op
                 createUser·p0.9999: 20.763 ms/op
                 createUser·p1.00:   22.086 ms/op

Iteration   2: 3.968 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   7.148 ms/op
                 createUser·p0.999:  21.901 ms/op
                 createUser·p0.9999: 27.940 ms/op
                 createUser·p1.00:   28.967 ms/op

Iteration   3: 3.933 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  23.265 ms/op
                 createUser·p0.9999: 24.838 ms/op
                 createUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235467
  mean =      4.075 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 350 
    [ 2.500,  5.000) = 218029 
    [ 5.000,  7.500) = 14697 
    [ 7.500, 10.000) = 1469 
    [10.000, 12.500) = 466 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     20.185 ms/op
     p(99.9900) =     26.268 ms/op
     p(99.9990) =     28.679 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 14.064 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 4.759 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.013 ms/op
Iteration   1: 3.831 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   2.183 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   6.873 ms/op
                 existUser·p0.999:  12.370 ms/op
                 existUser·p0.9999: 25.100 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   2: 3.901 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.935 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   5.022 ms/op
                 existUser·p0.99:   7.666 ms/op
                 existUser·p0.999:  26.575 ms/op
                 existUser·p0.9999: 32.702 ms/op
                 existUser·p1.00:   33.554 ms/op

Iteration   3: 3.905 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.989 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.973 ms/op
                 existUser·p0.99:   6.898 ms/op
                 existUser·p0.999:  14.682 ms/op
                 existUser·p0.9999: 29.630 ms/op
                 existUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247302
  mean =      3.879 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 295 
    [ 2.500,  5.000) = 235524 
    [ 5.000,  7.500) = 9347 
    [ 7.500, 10.000) = 1490 
    [10.000, 12.500) = 331 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.935 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     14.510 ms/op
     p(99.9900) =     31.630 ms/op
     p(99.9990) =     33.279 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 13.657 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 5.182 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.258 ±(99.9%) 0.014 ms/op
Iteration   1: 4.155 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   8.143 ms/op
                 getUser·p0.999:  22.415 ms/op
                 getUser·p0.9999: 31.162 ms/op
                 getUser·p1.00:   31.752 ms/op

Iteration   2: 3.880 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.028 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  26.083 ms/op
                 getUser·p0.9999: 28.033 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 4.262 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.933 ms/op
                 getUser·p0.50:   4.051 ms/op
                 getUser·p0.90:   5.112 ms/op
                 getUser·p0.95:   6.398 ms/op
                 getUser·p0.99:   7.979 ms/op
                 getUser·p0.999:  12.583 ms/op
                 getUser·p0.9999: 34.603 ms/op
                 getUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234451
  mean =      4.093 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 106 
    [ 2.500,  5.000) = 219126 
    [ 5.000,  7.500) = 12690 
    [ 7.500, 10.000) = 1879 
    [10.000, 12.500) = 355 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     22.515 ms/op
     p(99.9900) =     32.680 ms/op
     p(99.9990) =     35.231 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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
# Warmup Iteration   1: 14.325 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 5.550 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.153 ±(99.9%) 0.024 ms/op
Iteration   1: 4.834 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.576 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  26.929 ms/op
                 listUser·p0.9999: 29.864 ms/op
                 listUser·p1.00:   31.850 ms/op

Iteration   2: 4.666 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.511 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  19.185 ms/op
                 listUser·p0.9999: 35.858 ms/op
                 listUser·p1.00:   36.372 ms/op

Iteration   3: 4.614 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.638 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  18.809 ms/op
                 listUser·p0.9999: 21.733 ms/op
                 listUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204079
  mean =      4.703 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 175068 
    [ 5.000,  7.500) = 24149 
    [ 7.500, 10.000) = 3595 
    [10.000, 12.500) = 617 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.511 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      9.011 ms/op
     p(99.9000) =     20.480 ms/op
     p(99.9900) =     33.620 ms/op
     p(99.9990) =     36.233 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.664 ± 3.004  ops/ms
ClientPb.existUser                       thrpt       3   8.341 ± 3.611  ops/ms
ClientPb.getUser                         thrpt       3   7.700 ± 4.607  ops/ms
ClientPb.listUser                        thrpt       3   6.832 ± 0.436  ops/ms
ClientPb.createUser                       avgt       3   3.887 ± 1.248   ms/op
ClientPb.existUser                        avgt       3   3.829 ± 1.265   ms/op
ClientPb.getUser                          avgt       3   3.993 ± 1.810   ms/op
ClientPb.listUser                         avgt       3   4.665 ± 2.420   ms/op
ClientPb.createUser                     sample  235467   4.075 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.167           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.825           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.300           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.528           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.185           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.268           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.967           ms/op
ClientPb.existUser                      sample  247302   3.879 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.935           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.307           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.510           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.630           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.554           ms/op
ClientPb.getUser                        sample  234451   4.093 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.726           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.661           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.341           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.619           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.515           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.680           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.389           ms/op
ClientPb.listUser                       sample  204079   4.703 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.511           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.011           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.480           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.620           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.372           ms/op
