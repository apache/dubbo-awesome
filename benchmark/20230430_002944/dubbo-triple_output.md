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
# Warmup Iteration   1: 1.011 ops/ms
# Warmup Iteration   2: 2.115 ops/ms
# Warmup Iteration   3: 4.379 ops/ms
Iteration   1: 5.262 ops/ms
Iteration   2: 5.456 ops/ms
Iteration   3: 5.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.486 ±(99.9%) 4.374 ops/ms [Average]
  (min, avg, max) = (5.262, 5.486, 5.739), stdev = 0.240
  CI (99.9%): [1.111, 9.860] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.503 ops/ms
# Warmup Iteration   2: 4.545 ops/ms
# Warmup Iteration   3: 5.523 ops/ms
Iteration   1: 5.732 ops/ms
Iteration   2: 5.943 ops/ms
Iteration   3: 5.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.816 ±(99.9%) 2.038 ops/ms [Average]
  (min, avg, max) = (5.732, 5.816, 5.943), stdev = 0.112
  CI (99.9%): [3.778, 7.854] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.484 ops/ms
# Warmup Iteration   2: 3.710 ops/ms
# Warmup Iteration   3: 5.381 ops/ms
Iteration   1: 5.517 ops/ms
Iteration   2: 5.599 ops/ms
Iteration   3: 5.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.636 ±(99.9%) 2.564 ops/ms [Average]
  (min, avg, max) = (5.517, 5.636, 5.791), stdev = 0.141
  CI (99.9%): [3.072, 8.200] (assumes normal distribution)


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
# Warmup Iteration   1: 1.380 ops/ms
# Warmup Iteration   2: 3.680 ops/ms
# Warmup Iteration   3: 4.524 ops/ms
Iteration   1: 4.802 ops/ms
Iteration   2: 4.814 ops/ms
Iteration   3: 4.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.830 ±(99.9%) 0.703 ops/ms [Average]
  (min, avg, max) = (4.802, 4.830, 4.874), stdev = 0.039
  CI (99.9%): [4.127, 5.532] (assumes normal distribution)


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
# Warmup Iteration   1: 18.691 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 7.277 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.891 ±(99.9%) 0.014 ms/op
Iteration   1: 6.039 ±(99.9%) 0.009 ms/op
Iteration   2: 5.620 ±(99.9%) 0.022 ms/op
Iteration   3: 5.780 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.813 ±(99.9%) 3.862 ms/op [Average]
  (min, avg, max) = (5.620, 5.813, 6.039), stdev = 0.212
  CI (99.9%): [1.952, 9.675] (assumes normal distribution)


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
# Warmup Iteration   1: 17.663 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 6.784 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.699 ±(99.9%) 0.007 ms/op
Iteration   1: 5.573 ±(99.9%) 0.006 ms/op
Iteration   2: 5.504 ±(99.9%) 0.011 ms/op
Iteration   3: 5.496 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.524 ±(99.9%) 0.772 ms/op [Average]
  (min, avg, max) = (5.496, 5.524, 5.573), stdev = 0.042
  CI (99.9%): [4.752, 6.297] (assumes normal distribution)


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
# Warmup Iteration   1: 19.006 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 6.785 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.905 ±(99.9%) 0.006 ms/op
Iteration   1: 5.581 ±(99.9%) 0.010 ms/op
Iteration   2: 5.502 ±(99.9%) 0.013 ms/op
Iteration   3: 5.544 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.542 ±(99.9%) 0.724 ms/op [Average]
  (min, avg, max) = (5.502, 5.542, 5.581), stdev = 0.040
  CI (99.9%): [4.818, 6.266] (assumes normal distribution)


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
# Warmup Iteration   1: 20.821 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 7.429 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.739 ±(99.9%) 0.013 ms/op
Iteration   1: 6.590 ±(99.9%) 0.010 ms/op
Iteration   2: 6.565 ±(99.9%) 0.014 ms/op
Iteration   3: 6.688 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.614 ±(99.9%) 1.184 ms/op [Average]
  (min, avg, max) = (6.565, 6.614, 6.688), stdev = 0.065
  CI (99.9%): [5.430, 7.799] (assumes normal distribution)


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
# Warmup Iteration   1: 19.448 ±(99.9%) 0.307 ms/op
# Warmup Iteration   2: 7.326 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.048 ±(99.9%) 0.027 ms/op
Iteration   1: 5.603 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.236 ms/op
                 createUser·p0.50:   5.267 ms/op
                 createUser·p0.90:   6.849 ms/op
                 createUser·p0.95:   7.954 ms/op
                 createUser·p0.99:   10.895 ms/op
                 createUser·p0.999:  14.564 ms/op
                 createUser·p0.9999: 28.148 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   2: 5.687 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   5.390 ms/op
                 createUser·p0.90:   7.012 ms/op
                 createUser·p0.95:   8.036 ms/op
                 createUser·p0.99:   10.437 ms/op
                 createUser·p0.999:  26.932 ms/op
                 createUser·p0.9999: 34.480 ms/op
                 createUser·p1.00:   35.586 ms/op

Iteration   3: 5.794 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.650 ms/op
                 createUser·p0.50:   5.431 ms/op
                 createUser·p0.90:   7.201 ms/op
                 createUser·p0.95:   8.208 ms/op
                 createUser·p0.99:   11.289 ms/op
                 createUser·p0.999:  29.121 ms/op
                 createUser·p0.9999: 33.522 ms/op
                 createUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168521
  mean =      5.693 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 50472 
    [ 5.000,  7.500) = 105889 
    [ 7.500, 10.000) = 9523 
    [10.000, 12.500) = 1922 
    [12.500, 15.000) = 429 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      7.029 ms/op
     p(95.0000) =      8.061 ms/op
     p(99.0000) =     10.994 ms/op
     p(99.9000) =     21.627 ms/op
     p(99.9900) =     33.494 ms/op
     p(99.9990) =     36.040 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 18.387 ±(99.9%) 0.310 ms/op
# Warmup Iteration   2: 6.290 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.563 ±(99.9%) 0.021 ms/op
Iteration   1: 5.719 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.673 ms/op
                 existUser·p0.50:   5.325 ms/op
                 existUser·p0.90:   7.250 ms/op
                 existUser·p0.95:   8.274 ms/op
                 existUser·p0.99:   11.715 ms/op
                 existUser·p0.999:  16.730 ms/op
                 existUser·p0.9999: 30.048 ms/op
                 existUser·p1.00:   31.392 ms/op

Iteration   2: 5.387 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.668 ms/op
                 existUser·p0.95:   7.545 ms/op
                 existUser·p0.99:   9.880 ms/op
                 existUser·p0.999:  26.606 ms/op
                 existUser·p0.9999: 31.986 ms/op
                 existUser·p1.00:   33.096 ms/op

Iteration   3: 5.558 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   5.210 ms/op
                 existUser·p0.90:   6.963 ms/op
                 existUser·p0.95:   8.020 ms/op
                 existUser·p0.99:   10.776 ms/op
                 existUser·p0.999:  29.032 ms/op
                 existUser·p0.9999: 34.669 ms/op
                 existUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 172767
  mean =      5.551 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 62010 
    [ 5.000,  7.500) = 99013 
    [ 7.500, 10.000) = 9247 
    [10.000, 12.500) = 1526 
    [12.500, 15.000) = 521 
    [15.000, 17.500) = 204 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.980 ms/op
     p(95.0000) =      7.922 ms/op
     p(99.0000) =     10.764 ms/op
     p(99.9000) =     19.275 ms/op
     p(99.9900) =     33.798 ms/op
     p(99.9990) =     34.800 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 16.808 ±(99.9%) 0.255 ms/op
# Warmup Iteration   2: 6.730 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.969 ±(99.9%) 0.020 ms/op
Iteration   1: 5.931 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.683 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   7.926 ms/op
                 getUser·p0.95:   9.437 ms/op
                 getUser·p0.99:   13.953 ms/op
                 getUser·p0.999:  23.267 ms/op
                 getUser·p0.9999: 30.212 ms/op
                 getUser·p1.00:   30.376 ms/op

Iteration   2: 5.898 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.142 ms/op
                 getUser·p0.50:   5.530 ms/op
                 getUser·p0.90:   7.438 ms/op
                 getUser·p0.95:   8.569 ms/op
                 getUser·p0.99:   11.567 ms/op
                 getUser·p0.999:  27.320 ms/op
                 getUser·p0.9999: 30.428 ms/op
                 getUser·p1.00:   31.097 ms/op

Iteration   3: 5.845 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.528 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   7.479 ms/op
                 getUser·p0.95:   8.618 ms/op
                 getUser·p0.99:   12.239 ms/op
                 getUser·p0.999:  30.756 ms/op
                 getUser·p0.9999: 35.787 ms/op
                 getUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 162894
  mean =      5.891 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 44757 
    [ 5.000,  7.500) = 101104 
    [ 7.500, 10.000) = 12393 
    [10.000, 12.500) = 2970 
    [12.500, 15.000) = 865 
    [15.000, 17.500) = 396 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      5.423 ms/op
     p(90.0000) =      7.578 ms/op
     p(95.0000) =      8.815 ms/op
     p(99.0000) =     12.599 ms/op
     p(99.9000) =     24.612 ms/op
     p(99.9900) =     33.694 ms/op
     p(99.9990) =     36.290 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 19.144 ±(99.9%) 0.337 ms/op
# Warmup Iteration   2: 8.065 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.741 ±(99.9%) 0.030 ms/op
Iteration   1: 6.661 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.150 ms/op
                 listUser·p0.50:   6.283 ms/op
                 listUser·p0.90:   8.167 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   12.321 ms/op
                 listUser·p0.999:  25.526 ms/op
                 listUser·p0.9999: 29.216 ms/op
                 listUser·p1.00:   30.048 ms/op

Iteration   2: 6.571 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   6.242 ms/op
                 listUser·p0.90:   7.848 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   11.730 ms/op
                 listUser·p0.999:  28.452 ms/op
                 listUser·p0.9999: 32.244 ms/op
                 listUser·p1.00:   33.030 ms/op

Iteration   3: 6.577 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.498 ms/op
                 listUser·p0.50:   6.210 ms/op
                 listUser·p0.90:   7.913 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   11.951 ms/op
                 listUser·p0.999:  26.160 ms/op
                 listUser·p0.9999: 30.959 ms/op
                 listUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145382
  mean =      6.603 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 3590 
    [ 5.000,  7.500) = 119164 
    [ 7.500, 10.000) = 17926 
    [10.000, 12.500) = 3512 
    [12.500, 15.000) = 628 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 92 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.245 ms/op
     p(50.0000) =      6.242 ms/op
     p(90.0000) =      7.987 ms/op
     p(95.0000) =      9.126 ms/op
     p(99.0000) =     12.042 ms/op
     p(99.9000) =     27.034 ms/op
     p(99.9900) =     30.827 ms/op
     p(99.9990) =     33.015 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.486 ± 4.374  ops/ms
ClientPb.existUser                       thrpt       3   5.816 ± 2.038  ops/ms
ClientPb.getUser                         thrpt       3   5.636 ± 2.564  ops/ms
ClientPb.listUser                        thrpt       3   4.830 ± 0.703  ops/ms
ClientPb.createUser                       avgt       3   5.813 ± 3.862   ms/op
ClientPb.existUser                        avgt       3   5.524 ± 0.772   ms/op
ClientPb.getUser                          avgt       3   5.542 ± 0.724   ms/op
ClientPb.listUser                         avgt       3   6.614 ± 1.184   ms/op
ClientPb.createUser                     sample  168521   5.693 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.464           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.366           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.029           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.061           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.994           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.627           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.494           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.028           ms/op
ClientPb.existUser                      sample  172767   5.551 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.818           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.194           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.980           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.922           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.764           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.275           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.798           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.800           ms/op
ClientPb.getUser                        sample  162894   5.891 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.528           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.423           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.578           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.815           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.599           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.612           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.694           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.372           ms/op
ClientPb.listUser                       sample  145382   6.603 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.245           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.242           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.987           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.126           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.042           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.034           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.827           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.030           ms/op
