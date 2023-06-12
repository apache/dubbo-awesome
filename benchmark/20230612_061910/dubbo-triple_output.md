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
# Warmup Iteration   1: 1.072 ops/ms
# Warmup Iteration   2: 2.188 ops/ms
# Warmup Iteration   3: 4.925 ops/ms
Iteration   1: 5.248 ops/ms
Iteration   2: 5.388 ops/ms
Iteration   3: 5.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.416 ±(99.9%) 3.354 ops/ms [Average]
  (min, avg, max) = (5.248, 5.416, 5.613), stdev = 0.184
  CI (99.9%): [2.063, 8.770] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.586 ops/ms
# Warmup Iteration   2: 4.880 ops/ms
# Warmup Iteration   3: 5.731 ops/ms
Iteration   1: 6.073 ops/ms
Iteration   2: 5.808 ops/ms
Iteration   3: 6.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.974 ±(99.9%) 2.635 ops/ms [Average]
  (min, avg, max) = (5.808, 5.974, 6.073), stdev = 0.144
  CI (99.9%): [3.339, 8.608] (assumes normal distribution)


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
# Warmup Iteration   1: 1.595 ops/ms
# Warmup Iteration   2: 4.350 ops/ms
# Warmup Iteration   3: 5.240 ops/ms
Iteration   1: 5.411 ops/ms
Iteration   2: 5.542 ops/ms
Iteration   3: 5.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.511 ±(99.9%) 1.634 ops/ms [Average]
  (min, avg, max) = (5.411, 5.511, 5.582), stdev = 0.090
  CI (99.9%): [3.878, 7.145] (assumes normal distribution)


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
# Warmup Iteration   1: 1.591 ops/ms
# Warmup Iteration   2: 3.796 ops/ms
# Warmup Iteration   3: 4.472 ops/ms
Iteration   1: 4.704 ops/ms
Iteration   2: 4.633 ops/ms
Iteration   3: 4.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.678 ±(99.9%) 0.712 ops/ms [Average]
  (min, avg, max) = (4.633, 4.678, 4.704), stdev = 0.039
  CI (99.9%): [3.966, 5.389] (assumes normal distribution)


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
# Warmup Iteration   1: 19.538 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 6.904 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.219 ±(99.9%) 0.010 ms/op
Iteration   1: 5.649 ±(99.9%) 0.006 ms/op
Iteration   2: 5.680 ±(99.9%) 0.013 ms/op
Iteration   3: 5.733 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.687 ±(99.9%) 0.770 ms/op [Average]
  (min, avg, max) = (5.649, 5.687, 5.733), stdev = 0.042
  CI (99.9%): [4.917, 6.457] (assumes normal distribution)


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
# Warmup Iteration   1: 16.145 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.473 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.697 ±(99.9%) 0.008 ms/op
Iteration   1: 5.472 ±(99.9%) 0.014 ms/op
Iteration   2: 5.360 ±(99.9%) 0.014 ms/op
Iteration   3: 5.427 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.420 ±(99.9%) 1.030 ms/op [Average]
  (min, avg, max) = (5.360, 5.420, 5.472), stdev = 0.056
  CI (99.9%): [4.390, 6.450] (assumes normal distribution)


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
# Warmup Iteration   1: 18.994 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 7.041 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.097 ±(99.9%) 0.009 ms/op
Iteration   1: 5.969 ±(99.9%) 0.011 ms/op
Iteration   2: 5.715 ±(99.9%) 0.013 ms/op
Iteration   3: 5.701 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.795 ±(99.9%) 2.756 ms/op [Average]
  (min, avg, max) = (5.701, 5.795, 5.969), stdev = 0.151
  CI (99.9%): [3.039, 8.551] (assumes normal distribution)


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
# Warmup Iteration   1: 20.213 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 7.900 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.719 ±(99.9%) 0.014 ms/op
Iteration   1: 6.977 ±(99.9%) 0.014 ms/op
Iteration   2: 6.698 ±(99.9%) 0.021 ms/op
Iteration   3: 6.778 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.818 ±(99.9%) 2.622 ms/op [Average]
  (min, avg, max) = (6.698, 6.818, 6.977), stdev = 0.144
  CI (99.9%): [4.195, 9.440] (assumes normal distribution)


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
# Warmup Iteration   1: 17.108 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 7.203 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.619 ±(99.9%) 0.036 ms/op
Iteration   1: 5.714 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.290 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   7.389 ms/op
                 createUser·p0.95:   8.249 ms/op
                 createUser·p0.99:   10.289 ms/op
                 createUser·p0.999:  18.020 ms/op
                 createUser·p0.9999: 35.206 ms/op
                 createUser·p1.00:   36.700 ms/op

Iteration   2: 5.853 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.204 ms/op
                 createUser·p0.50:   5.595 ms/op
                 createUser·p0.90:   7.504 ms/op
                 createUser·p0.95:   8.356 ms/op
                 createUser·p0.99:   10.650 ms/op
                 createUser·p0.999:  26.475 ms/op
                 createUser·p0.9999: 32.628 ms/op
                 createUser·p1.00:   33.325 ms/op

Iteration   3: 5.708 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.989 ms/op
                 createUser·p0.50:   5.358 ms/op
                 createUser·p0.90:   7.250 ms/op
                 createUser·p0.95:   8.176 ms/op
                 createUser·p0.99:   10.715 ms/op
                 createUser·p0.999:  30.538 ms/op
                 createUser·p0.9999: 35.451 ms/op
                 createUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 166735
  mean =      5.758 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 55845 
    [ 5.000,  7.500) = 95595 
    [ 7.500, 10.000) = 12949 
    [10.000, 12.500) = 1707 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 74 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.989 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      7.389 ms/op
     p(95.0000) =      8.266 ms/op
     p(99.0000) =     10.551 ms/op
     p(99.9000) =     21.472 ms/op
     p(99.9900) =     34.472 ms/op
     p(99.9990) =     36.656 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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
# Warmup Iteration   1: 17.162 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 6.433 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.741 ±(99.9%) 0.021 ms/op
Iteration   1: 5.688 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.915 ms/op
                 existUser·p0.50:   5.423 ms/op
                 existUser·p0.90:   7.397 ms/op
                 existUser·p0.95:   8.241 ms/op
                 existUser·p0.99:   10.732 ms/op
                 existUser·p0.999:  17.031 ms/op
                 existUser·p0.9999: 27.505 ms/op
                 existUser·p1.00:   29.655 ms/op

Iteration   2: 5.613 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.150 ms/op
                 existUser·p0.50:   5.317 ms/op
                 existUser·p0.90:   7.168 ms/op
                 existUser·p0.95:   8.004 ms/op
                 existUser·p0.99:   10.453 ms/op
                 existUser·p0.999:  27.525 ms/op
                 existUser·p0.9999: 31.631 ms/op
                 existUser·p1.00:   32.637 ms/op

Iteration   3: 5.815 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.306 ms/op
                 existUser·p0.50:   5.505 ms/op
                 existUser·p0.90:   7.561 ms/op
                 existUser·p0.95:   8.372 ms/op
                 existUser·p0.99:   10.617 ms/op
                 existUser·p0.999:  28.673 ms/op
                 existUser·p0.9999: 35.554 ms/op
                 existUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 168287
  mean =      5.704 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 57724 
    [ 5.000,  7.500) = 95291 
    [ 7.500, 10.000) = 12831 
    [10.000, 12.500) = 1660 
    [12.500, 15.000) = 434 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.915 ms/op
     p(50.0000) =      5.415 ms/op
     p(90.0000) =      7.373 ms/op
     p(95.0000) =      8.217 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     19.094 ms/op
     p(99.9900) =     32.812 ms/op
     p(99.9990) =     36.604 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


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
# Warmup Iteration   1: 18.053 ±(99.9%) 0.293 ms/op
# Warmup Iteration   2: 6.589 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.855 ±(99.9%) 0.024 ms/op
Iteration   1: 5.865 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.572 ms/op
                 getUser·p0.50:   5.546 ms/op
                 getUser·p0.90:   7.578 ms/op
                 getUser·p0.95:   8.602 ms/op
                 getUser·p0.99:   11.420 ms/op
                 getUser·p0.999:  18.758 ms/op
                 getUser·p0.9999: 28.201 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   2: 5.706 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.585 ms/op
                 getUser·p0.50:   5.292 ms/op
                 getUser·p0.90:   7.348 ms/op
                 getUser·p0.95:   8.536 ms/op
                 getUser·p0.99:   12.272 ms/op
                 getUser·p0.999:  27.225 ms/op
                 getUser·p0.9999: 31.804 ms/op
                 getUser·p1.00:   32.342 ms/op

Iteration   3: 5.967 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.859 ms/op
                 getUser·p0.50:   5.685 ms/op
                 getUser·p0.90:   7.733 ms/op
                 getUser·p0.95:   8.602 ms/op
                 getUser·p0.99:   10.840 ms/op
                 getUser·p0.999:  27.888 ms/op
                 getUser·p0.9999: 34.639 ms/op
                 getUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 164254
  mean =      5.844 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 49415 
    [ 5.000,  7.500) = 97569 
    [ 7.500, 10.000) = 13706 
    [10.000, 12.500) = 2528 
    [12.500, 15.000) = 541 
    [15.000, 17.500) = 236 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.572 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      7.578 ms/op
     p(95.0000) =      8.569 ms/op
     p(99.0000) =     11.452 ms/op
     p(99.9000) =     23.921 ms/op
     p(99.9900) =     32.595 ms/op
     p(99.9990) =     35.609 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 19.344 ±(99.9%) 0.331 ms/op
# Warmup Iteration   2: 8.316 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 6.825 ±(99.9%) 0.031 ms/op
Iteration   1: 6.806 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   6.332 ms/op
                 listUser·p0.90:   8.847 ms/op
                 listUser·p0.95:   9.912 ms/op
                 listUser·p0.99:   13.566 ms/op
                 listUser·p0.999:  33.098 ms/op
                 listUser·p0.9999: 43.334 ms/op
                 listUser·p1.00:   44.368 ms/op

Iteration   2: 6.931 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.236 ms/op
                 listUser·p0.50:   6.644 ms/op
                 listUser·p0.90:   8.749 ms/op
                 listUser·p0.95:   9.748 ms/op
                 listUser·p0.99:   12.796 ms/op
                 listUser·p0.999:  31.667 ms/op
                 listUser·p0.9999: 34.562 ms/op
                 listUser·p1.00:   34.996 ms/op

Iteration   3: 7.006 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.113 ms/op
                 listUser·p0.50:   6.545 ms/op
                 listUser·p0.90:   8.962 ms/op
                 listUser·p0.95:   10.132 ms/op
                 listUser·p0.99:   13.107 ms/op
                 listUser·p0.999:  26.509 ms/op
                 listUser·p0.9999: 31.588 ms/op
                 listUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 138773
  mean =      6.913 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4615 
    [ 5.000, 10.000) = 127502 
    [10.000, 15.000) = 5911 
    [15.000, 20.000) = 423 
    [20.000, 25.000) = 60 
    [25.000, 30.000) = 76 
    [30.000, 35.000) = 154 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.933 ms/op
     p(50.0000) =      6.504 ms/op
     p(90.0000) =      8.847 ms/op
     p(95.0000) =      9.929 ms/op
     p(99.0000) =     13.140 ms/op
     p(99.9000) =     31.039 ms/op
     p(99.9900) =     39.592 ms/op
     p(99.9990) =     44.139 ms/op
     p(99.9999) =     44.368 ms/op
    p(100.0000) =     44.368 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.416 ± 3.354  ops/ms
ClientPb.existUser                       thrpt       3   5.974 ± 2.635  ops/ms
ClientPb.getUser                         thrpt       3   5.511 ± 1.634  ops/ms
ClientPb.listUser                        thrpt       3   4.678 ± 0.712  ops/ms
ClientPb.createUser                       avgt       3   5.687 ± 0.770   ms/op
ClientPb.existUser                        avgt       3   5.420 ± 1.030   ms/op
ClientPb.getUser                          avgt       3   5.795 ± 2.756   ms/op
ClientPb.listUser                         avgt       3   6.818 ± 2.622   ms/op
ClientPb.createUser                     sample  166735   5.758 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.989           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.389           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.266           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.551           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.472           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.472           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.700           ms/op
ClientPb.existUser                      sample  168287   5.704 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.915           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.373           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.217           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.617           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.094           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.812           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.962           ms/op
ClientPb.getUser                        sample  164254   5.844 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.513           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.578           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.569           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.452           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.921           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.595           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.652           ms/op
ClientPb.listUser                       sample  138773   6.913 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.933           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.504           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.929           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.140           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.039           ms/op
ClientPb.listUser:listUser·p0.9999      sample          39.592           ms/op
ClientPb.listUser:listUser·p1.00        sample          44.368           ms/op
