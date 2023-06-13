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
# Warmup Iteration   1: 1.610 ops/ms
# Warmup Iteration   2: 3.350 ops/ms
# Warmup Iteration   3: 6.782 ops/ms
Iteration   1: 7.700 ops/ms
Iteration   2: 7.947 ops/ms
Iteration   3: 7.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.836 ±(99.9%) 2.286 ops/ms [Average]
  (min, avg, max) = (7.700, 7.836, 7.947), stdev = 0.125
  CI (99.9%): [5.550, 10.123] (assumes normal distribution)


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
# Warmup Iteration   1: 2.391 ops/ms
# Warmup Iteration   2: 7.068 ops/ms
# Warmup Iteration   3: 8.002 ops/ms
Iteration   1: 8.386 ops/ms
Iteration   2: 8.227 ops/ms
Iteration   3: 8.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.290 ±(99.9%) 1.542 ops/ms [Average]
  (min, avg, max) = (8.227, 8.290, 8.386), stdev = 0.085
  CI (99.9%): [6.748, 9.832] (assumes normal distribution)


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
# Warmup Iteration   1: 2.267 ops/ms
# Warmup Iteration   2: 6.981 ops/ms
# Warmup Iteration   3: 8.010 ops/ms
Iteration   1: 8.219 ops/ms
Iteration   2: 7.811 ops/ms
Iteration   3: 8.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.068 ±(99.9%) 4.093 ops/ms [Average]
  (min, avg, max) = (7.811, 8.068, 8.219), stdev = 0.224
  CI (99.9%): [3.975, 12.161] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.012 ops/ms
# Warmup Iteration   2: 5.160 ops/ms
# Warmup Iteration   3: 6.768 ops/ms
Iteration   1: 6.614 ops/ms
Iteration   2: 6.860 ops/ms
Iteration   3: 7.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.862 ±(99.9%) 4.534 ops/ms [Average]
  (min, avg, max) = (6.614, 6.862, 7.111), stdev = 0.249
  CI (99.9%): [2.327, 11.396] (assumes normal distribution)


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
# Warmup Iteration   1: 13.246 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.781 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.370 ±(99.9%) 0.008 ms/op
Iteration   1: 4.017 ±(99.9%) 0.006 ms/op
Iteration   2: 3.974 ±(99.9%) 0.012 ms/op
Iteration   3: 3.927 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.973 ±(99.9%) 0.819 ms/op [Average]
  (min, avg, max) = (3.927, 3.973, 4.017), stdev = 0.045
  CI (99.9%): [3.154, 4.792] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.675 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.009 ms/op
Iteration   1: 3.845 ±(99.9%) 0.005 ms/op
Iteration   2: 3.843 ±(99.9%) 0.009 ms/op
Iteration   3: 3.834 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.841 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (3.834, 3.841, 3.845), stdev = 0.006
  CI (99.9%): [3.733, 3.948] (assumes normal distribution)


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
# Warmup Iteration   1: 14.022 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.524 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.009 ms/op
Iteration   1: 3.964 ±(99.9%) 0.009 ms/op
Iteration   2: 3.917 ±(99.9%) 0.005 ms/op
Iteration   3: 3.990 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.957 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (3.917, 3.957, 3.990), stdev = 0.037
  CI (99.9%): [3.278, 4.636] (assumes normal distribution)


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
# Warmup Iteration   1: 14.233 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.556 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.800 ±(99.9%) 0.009 ms/op
Iteration   1: 4.640 ±(99.9%) 0.012 ms/op
Iteration   2: 4.730 ±(99.9%) 0.014 ms/op
Iteration   3: 4.644 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.671 ±(99.9%) 0.931 ms/op [Average]
  (min, avg, max) = (4.640, 4.671, 4.730), stdev = 0.051
  CI (99.9%): [3.740, 5.603] (assumes normal distribution)


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
# Warmup Iteration   1: 14.161 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 5.034 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.268 ±(99.9%) 0.017 ms/op
Iteration   1: 4.039 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.554 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   7.504 ms/op
                 createUser·p0.999:  12.785 ms/op
                 createUser·p0.9999: 25.204 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   2: 4.059 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.780 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.087 ms/op
                 createUser·p0.99:   6.750 ms/op
                 createUser·p0.999:  24.397 ms/op
                 createUser·p0.9999: 30.158 ms/op
                 createUser·p1.00:   30.769 ms/op

Iteration   3: 4.139 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   8.184 ms/op
                 createUser·p0.999:  24.641 ms/op
                 createUser·p0.9999: 31.392 ms/op
                 createUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235347
  mean =      4.079 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 319 
    [ 2.500,  5.000) = 219280 
    [ 5.000,  7.500) = 13270 
    [ 7.500, 10.000) = 1945 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     23.233 ms/op
     p(99.9900) =     30.162 ms/op
     p(99.9990) =     31.425 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


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
# Warmup Iteration   1: 11.569 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.174 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.011 ms/op
Iteration   1: 3.964 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.946 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   6.611 ms/op
                 existUser·p0.999:  22.752 ms/op
                 existUser·p0.9999: 25.196 ms/op
                 existUser·p1.00:   26.444 ms/op

Iteration   2: 3.934 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   2.023 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   5.284 ms/op
                 existUser·p0.99:   7.571 ms/op
                 existUser·p0.999:  12.304 ms/op
                 existUser·p0.9999: 29.737 ms/op
                 existUser·p1.00:   30.114 ms/op

Iteration   3: 3.854 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   4.911 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  10.764 ms/op
                 existUser·p0.9999: 30.301 ms/op
                 existUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244925
  mean =      3.917 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 361 
    [ 2.500,  5.000) = 230134 
    [ 5.000,  7.500) = 12836 
    [ 7.500, 10.000) = 1221 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.561 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     12.357 ms/op
     p(99.9900) =     29.884 ms/op
     p(99.9990) =     33.011 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 12.935 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 4.653 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.015 ms/op
Iteration   1: 4.074 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.232 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   5.761 ms/op
                 getUser·p0.99:   8.602 ms/op
                 getUser·p0.999:  24.519 ms/op
                 getUser·p0.9999: 31.899 ms/op
                 getUser·p1.00:   33.161 ms/op

Iteration   2: 3.972 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.322 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  12.263 ms/op
                 getUser·p0.9999: 27.360 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   3: 3.996 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  27.684 ms/op
                 getUser·p0.9999: 31.422 ms/op
                 getUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239031
  mean =      4.013 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 226868 
    [ 5.000,  7.500) = 9372 
    [ 7.500, 10.000) = 1897 
    [10.000, 12.500) = 487 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     24.313 ms/op
     p(99.9900) =     31.264 ms/op
     p(99.9990) =     32.694 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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
# Warmup Iteration   1: 15.090 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 5.391 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.857 ±(99.9%) 0.020 ms/op
Iteration   1: 4.823 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   6.332 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  25.222 ms/op
                 listUser·p0.9999: 28.795 ms/op
                 listUser·p1.00:   29.327 ms/op

Iteration   2: 4.717 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.716 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  19.956 ms/op
                 listUser·p0.9999: 23.233 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   3: 4.475 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.601 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   8.167 ms/op
                 listUser·p0.999:  15.820 ms/op
                 listUser·p0.9999: 18.210 ms/op
                 listUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205476
  mean =      4.667 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 180285 
    [ 5.000,  7.500) = 20374 
    [ 7.500, 10.000) = 3584 
    [10.000, 12.500) = 562 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      2.294 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     19.551 ms/op
     p(99.9900) =     28.112 ms/op
     p(99.9990) =     29.225 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.836 ± 2.286  ops/ms
ClientPb.existUser                       thrpt       3   8.290 ± 1.542  ops/ms
ClientPb.getUser                         thrpt       3   8.068 ± 4.093  ops/ms
ClientPb.listUser                        thrpt       3   6.862 ± 4.534  ops/ms
ClientPb.createUser                       avgt       3   3.973 ± 0.819   ms/op
ClientPb.existUser                        avgt       3   3.841 ± 0.107   ms/op
ClientPb.getUser                          avgt       3   3.957 ± 0.679   ms/op
ClientPb.listUser                         avgt       3   4.671 ± 0.931   ms/op
ClientPb.createUser                     sample  235347   4.079 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.298           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.817           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.161           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.553           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.233           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.162           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.457           ms/op
ClientPb.existUser                      sample  244925   3.917 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.561           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.530           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.357           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.884           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.948           ms/op
ClientPb.getUser                        sample  239031   4.013 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.444           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.014           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.627           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.313           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.264           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.161           ms/op
ClientPb.listUser                       sample  205476   4.667 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.294           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.087           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.946           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.551           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.112           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.327           ms/op
