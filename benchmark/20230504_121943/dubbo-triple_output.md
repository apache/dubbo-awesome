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
# Warmup Iteration   1: 1.910 ops/ms
# Warmup Iteration   2: 4.350 ops/ms
# Warmup Iteration   3: 7.686 ops/ms
Iteration   1: 7.828 ops/ms
Iteration   2: 8.222 ops/ms
Iteration   3: 8.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.123 ±(99.9%) 4.742 ops/ms [Average]
  (min, avg, max) = (7.828, 8.123, 8.318), stdev = 0.260
  CI (99.9%): [3.380, 12.865] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.196 ops/ms
# Warmup Iteration   2: 6.898 ops/ms
# Warmup Iteration   3: 7.963 ops/ms
Iteration   1: 8.485 ops/ms
Iteration   2: 8.435 ops/ms
Iteration   3: 8.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.589 ±(99.9%) 4.106 ops/ms [Average]
  (min, avg, max) = (8.435, 8.589, 8.847), stdev = 0.225
  CI (99.9%): [4.483, 12.695] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.233 ops/ms
# Warmup Iteration   2: 6.504 ops/ms
# Warmup Iteration   3: 7.844 ops/ms
Iteration   1: 8.095 ops/ms
Iteration   2: 8.135 ops/ms
Iteration   3: 7.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.065 ±(99.9%) 1.608 ops/ms [Average]
  (min, avg, max) = (7.966, 8.065, 8.135), stdev = 0.088
  CI (99.9%): [6.457, 9.674] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.341 ops/ms
# Warmup Iteration   2: 6.213 ops/ms
# Warmup Iteration   3: 6.568 ops/ms
Iteration   1: 6.995 ops/ms
Iteration   2: 7.249 ops/ms
Iteration   3: 7.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.125 ±(99.9%) 2.321 ops/ms [Average]
  (min, avg, max) = (6.995, 7.125, 7.249), stdev = 0.127
  CI (99.9%): [4.805, 9.446] (assumes normal distribution)


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
# Warmup Iteration   1: 12.034 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.390 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.331 ±(99.9%) 0.006 ms/op
Iteration   1: 3.932 ±(99.9%) 0.010 ms/op
Iteration   2: 3.924 ±(99.9%) 0.004 ms/op
Iteration   3: 3.958 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.938 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (3.924, 3.938, 3.958), stdev = 0.018
  CI (99.9%): [3.617, 4.259] (assumes normal distribution)


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
# Warmup Iteration   1: 10.680 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.759 ±(99.9%) 0.008 ms/op
Iteration   1: 3.817 ±(99.9%) 0.003 ms/op
Iteration   2: 3.837 ±(99.9%) 0.006 ms/op
Iteration   3: 3.747 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.800 ±(99.9%) 0.863 ms/op [Average]
  (min, avg, max) = (3.747, 3.800, 3.837), stdev = 0.047
  CI (99.9%): [2.937, 4.663] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.297 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.937 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.009 ms/op
Iteration   1: 4.045 ±(99.9%) 0.010 ms/op
Iteration   2: 4.383 ±(99.9%) 0.003 ms/op
Iteration   3: 3.997 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.142 ±(99.9%) 3.840 ms/op [Average]
  (min, avg, max) = (3.997, 4.142, 4.383), stdev = 0.210
  CI (99.9%): [0.302, 7.982] (assumes normal distribution)


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
# Warmup Iteration   1: 14.322 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.614 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.699 ±(99.9%) 0.015 ms/op
Iteration   1: 4.653 ±(99.9%) 0.013 ms/op
Iteration   2: 4.517 ±(99.9%) 0.006 ms/op
Iteration   3: 4.603 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.591 ±(99.9%) 1.259 ms/op [Average]
  (min, avg, max) = (4.517, 4.591, 4.653), stdev = 0.069
  CI (99.9%): [3.332, 5.849] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.333 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.872 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.260 ±(99.9%) 0.017 ms/op
Iteration   1: 3.885 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.364 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.836 ms/op
                 createUser·p0.999:  23.724 ms/op
                 createUser·p0.9999: 30.237 ms/op
                 createUser·p1.00:   31.031 ms/op

Iteration   2: 3.932 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.513 ms/op
                 createUser·p0.50:   3.797 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   6.275 ms/op
                 createUser·p0.999:  25.156 ms/op
                 createUser·p0.9999: 27.918 ms/op
                 createUser·p1.00:   28.475 ms/op

Iteration   3: 3.983 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.917 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  9.861 ms/op
                 createUser·p0.9999: 30.931 ms/op
                 createUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 243801
  mean =      3.933 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 331 
    [ 2.500,  5.000) = 234999 
    [ 5.000,  7.500) = 7300 
    [ 7.500, 10.000) = 669 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     23.698 ms/op
     p(99.9900) =     30.593 ms/op
     p(99.9990) =     31.437 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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
# Warmup Iteration   1: 13.294 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 4.468 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.012 ms/op
Iteration   1: 3.741 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.473 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   6.513 ms/op
                 existUser·p0.999:  21.760 ms/op
                 existUser·p0.9999: 28.326 ms/op
                 existUser·p1.00:   29.262 ms/op

Iteration   2: 3.859 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  10.306 ms/op
                 existUser·p0.9999: 27.376 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   3: 3.897 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.964 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.989 ms/op
                 existUser·p0.99:   6.742 ms/op
                 existUser·p0.999:  25.192 ms/op
                 existUser·p0.9999: 28.698 ms/op
                 existUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250280
  mean =      3.831 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 384 
    [ 2.500,  5.000) = 240169 
    [ 5.000,  7.500) = 8540 
    [ 7.500, 10.000) = 734 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 104 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     21.641 ms/op
     p(99.9900) =     28.311 ms/op
     p(99.9990) =     29.179 ms/op
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
# Warmup Iteration   1: 12.791 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.482 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.014 ms/op
Iteration   1: 3.930 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.954 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   8.348 ms/op
                 getUser·p0.999:  16.253 ms/op
                 getUser·p0.9999: 24.805 ms/op
                 getUser·p1.00:   25.854 ms/op

Iteration   2: 3.841 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.542 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  23.822 ms/op
                 getUser·p0.9999: 27.329 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   3: 3.705 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.505 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  10.830 ms/op
                 getUser·p0.9999: 33.775 ms/op
                 getUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 251148
  mean =      3.823 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 747 
    [ 2.500,  5.000) = 241325 
    [ 5.000,  7.500) = 6514 
    [ 7.500, 10.000) = 1939 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.505 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     15.738 ms/op
     p(99.9900) =     32.666 ms/op
     p(99.9990) =     34.144 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 13.857 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 5.160 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.829 ±(99.9%) 0.018 ms/op
Iteration   1: 4.637 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  24.347 ms/op
                 listUser·p0.9999: 27.963 ms/op
                 listUser·p1.00:   29.557 ms/op

Iteration   2: 4.555 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   8.663 ms/op
                 listUser·p0.999:  18.842 ms/op
                 listUser·p0.9999: 21.822 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   3: 4.288 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   4.227 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  16.871 ms/op
                 listUser·p0.9999: 18.335 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 213741
  mean =      4.488 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 196200 
    [ 5.000,  7.500) = 14122 
    [ 7.500, 10.000) = 2445 
    [10.000, 12.500) = 405 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     18.424 ms/op
     p(99.9900) =     25.612 ms/op
     p(99.9990) =     29.501 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.123 ± 4.742  ops/ms
ClientPb.existUser                       thrpt       3   8.589 ± 4.106  ops/ms
ClientPb.getUser                         thrpt       3   8.065 ± 1.608  ops/ms
ClientPb.listUser                        thrpt       3   7.125 ± 2.321  ops/ms
ClientPb.createUser                       avgt       3   3.938 ± 0.321   ms/op
ClientPb.existUser                        avgt       3   3.800 ± 0.863   ms/op
ClientPb.getUser                          avgt       3   4.142 ± 3.840   ms/op
ClientPb.listUser                         avgt       3   4.591 ± 1.259   ms/op
ClientPb.createUser                     sample  243801   3.933 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.364           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.489           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.817           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.455           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.698           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.593           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.178           ms/op
ClientPb.existUser                      sample  250280   3.831 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.473           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.383           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.801           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.578           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.641           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.311           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.130           ms/op
ClientPb.getUser                        sample  251148   3.823 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.505           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.669           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.537           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.738           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.666           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.734           ms/op
ClientPb.listUser                       sample  213741   4.488 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.370           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.235           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.339           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.424           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.612           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.557           ms/op
