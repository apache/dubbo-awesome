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
# Warmup Iteration   1: 1.538 ops/ms
# Warmup Iteration   2: 3.502 ops/ms
# Warmup Iteration   3: 7.278 ops/ms
Iteration   1: 7.829 ops/ms
Iteration   2: 8.339 ops/ms
Iteration   3: 8.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.093 ±(99.9%) 4.658 ops/ms [Average]
  (min, avg, max) = (7.829, 8.093, 8.339), stdev = 0.255
  CI (99.9%): [3.435, 12.751] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.218 ops/ms
# Warmup Iteration   2: 6.612 ops/ms
# Warmup Iteration   3: 8.394 ops/ms
Iteration   1: 8.763 ops/ms
Iteration   2: 8.391 ops/ms
Iteration   3: 8.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.580 ±(99.9%) 3.393 ops/ms [Average]
  (min, avg, max) = (8.391, 8.580, 8.763), stdev = 0.186
  CI (99.9%): [5.187, 11.973] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.213 ops/ms
# Warmup Iteration   2: 6.199 ops/ms
# Warmup Iteration   3: 8.086 ops/ms
Iteration   1: 8.008 ops/ms
Iteration   2: 8.037 ops/ms
Iteration   3: 7.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.007 ±(99.9%) 0.570 ops/ms [Average]
  (min, avg, max) = (7.975, 8.007, 8.037), stdev = 0.031
  CI (99.9%): [7.436, 8.577] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.189 ops/ms
# Warmup Iteration   2: 5.620 ops/ms
# Warmup Iteration   3: 6.753 ops/ms
Iteration   1: 6.888 ops/ms
Iteration   2: 7.009 ops/ms
Iteration   3: 7.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.007 ±(99.9%) 2.168 ops/ms [Average]
  (min, avg, max) = (6.888, 7.007, 7.125), stdev = 0.119
  CI (99.9%): [4.840, 9.175] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.057 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.013 ms/op
Iteration   1: 4.044 ±(99.9%) 0.007 ms/op
Iteration   2: 3.872 ±(99.9%) 0.009 ms/op
Iteration   3: 3.990 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.969 ±(99.9%) 1.603 ms/op [Average]
  (min, avg, max) = (3.872, 3.969, 4.044), stdev = 0.088
  CI (99.9%): [2.366, 5.572] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.477 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.006 ms/op
Iteration   1: 3.930 ±(99.9%) 0.007 ms/op
Iteration   2: 3.929 ±(99.9%) 0.004 ms/op
Iteration   3: 3.686 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.848 ±(99.9%) 2.569 ms/op [Average]
  (min, avg, max) = (3.686, 3.848, 3.930), stdev = 0.141
  CI (99.9%): [1.280, 6.417] (assumes normal distribution)


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
# Warmup Iteration   1: 12.776 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.196 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.004 ms/op
Iteration   1: 3.961 ±(99.9%) 0.007 ms/op
Iteration   2: 4.112 ±(99.9%) 0.010 ms/op
Iteration   3: 3.910 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.994 ±(99.9%) 1.921 ms/op [Average]
  (min, avg, max) = (3.910, 3.994, 4.112), stdev = 0.105
  CI (99.9%): [2.073, 5.916] (assumes normal distribution)


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
# Warmup Iteration   1: 13.444 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.156 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.849 ±(99.9%) 0.009 ms/op
Iteration   1: 4.658 ±(99.9%) 0.007 ms/op
Iteration   2: 4.694 ±(99.9%) 0.011 ms/op
Iteration   3: 4.622 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.658 ±(99.9%) 0.656 ms/op [Average]
  (min, avg, max) = (4.622, 4.658, 4.694), stdev = 0.036
  CI (99.9%): [4.002, 5.314] (assumes normal distribution)


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
# Warmup Iteration   1: 12.215 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.842 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.229 ±(99.9%) 0.017 ms/op
Iteration   1: 4.063 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.745 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   6.234 ms/op
                 createUser·p0.99:   8.552 ms/op
                 createUser·p0.999:  22.948 ms/op
                 createUser·p0.9999: 29.496 ms/op
                 createUser·p1.00:   29.786 ms/op

Iteration   2: 3.903 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.937 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   7.038 ms/op
                 createUser·p0.999:  24.711 ms/op
                 createUser·p0.9999: 33.083 ms/op
                 createUser·p1.00:   35.455 ms/op

Iteration   3: 3.865 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.839 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  12.635 ms/op
                 createUser·p0.9999: 31.350 ms/op
                 createUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 243250
  mean =      3.942 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 237 
    [ 2.500,  5.000) = 231538 
    [ 5.000,  7.500) = 8868 
    [ 7.500, 10.000) = 1878 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 65 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     22.831 ms/op
     p(99.9900) =     32.211 ms/op
     p(99.9990) =     33.479 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


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
# Warmup Iteration   1: 10.655 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.382 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.013 ms/op
Iteration   1: 3.823 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  23.703 ms/op
                 existUser·p0.9999: 25.613 ms/op
                 existUser·p1.00:   25.985 ms/op

Iteration   2: 3.869 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.968 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   6.539 ms/op
                 existUser·p0.999:  9.841 ms/op
                 existUser·p0.9999: 26.402 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   3: 3.751 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.048 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   6.283 ms/op
                 existUser·p0.999:  25.330 ms/op
                 existUser·p0.9999: 36.077 ms/op
                 existUser·p1.00:   36.504 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251457
  mean =      3.814 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 220 
    [ 2.500,  5.000) = 242203 
    [ 5.000,  7.500) = 7784 
    [ 7.500, 10.000) = 789 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 117 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.532 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     23.167 ms/op
     p(99.9900) =     34.311 ms/op
     p(99.9990) =     36.438 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


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
# Warmup Iteration   1: 12.371 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 5.420 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.013 ms/op
Iteration   1: 4.103 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.602 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.538 ms/op
                 getUser·p0.99:   8.929 ms/op
                 getUser·p0.999:  23.266 ms/op
                 getUser·p0.9999: 32.271 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   2: 3.862 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  26.391 ms/op
                 getUser·p0.9999: 32.988 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   3: 3.934 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.109 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  17.005 ms/op
                 getUser·p0.9999: 32.371 ms/op
                 getUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 242067
  mean =      3.964 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 232048 
    [ 5.000,  7.500) = 7434 
    [ 7.500, 10.000) = 1765 
    [10.000, 12.500) = 424 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 91 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     22.868 ms/op
     p(99.9900) =     32.368 ms/op
     p(99.9990) =     33.592 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 12.987 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 5.284 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.854 ±(99.9%) 0.018 ms/op
Iteration   1: 4.825 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   6.291 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  26.657 ms/op
                 listUser·p0.9999: 29.082 ms/op
                 listUser·p1.00:   30.048 ms/op

Iteration   2: 4.698 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.755 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   9.585 ms/op
                 listUser·p0.999:  18.219 ms/op
                 listUser·p0.9999: 24.530 ms/op
                 listUser·p1.00:   25.559 ms/op

Iteration   3: 4.578 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.826 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  16.083 ms/op
                 listUser·p0.9999: 18.810 ms/op
                 listUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204088
  mean =      4.698 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 175677 
    [ 5.000,  7.500) = 23070 
    [ 7.500, 10.000) = 3938 
    [10.000, 12.500) = 748 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 204 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      9.077 ms/op
     p(99.9000) =     18.314 ms/op
     p(99.9900) =     28.036 ms/op
     p(99.9990) =     29.985 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.093 ± 4.658  ops/ms
ClientPb.existUser                       thrpt       3   8.580 ± 3.393  ops/ms
ClientPb.getUser                         thrpt       3   8.007 ± 0.570  ops/ms
ClientPb.listUser                        thrpt       3   7.007 ± 2.168  ops/ms
ClientPb.createUser                       avgt       3   3.969 ± 1.603   ms/op
ClientPb.existUser                        avgt       3   3.848 ± 2.569   ms/op
ClientPb.getUser                          avgt       3   3.994 ± 1.921   ms/op
ClientPb.listUser                         avgt       3   4.658 ± 0.656   ms/op
ClientPb.createUser                     sample  243250   3.942 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.745           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.948           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.651           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.831           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.211           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.455           ms/op
ClientPb.existUser                      sample  251457   3.814 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.532           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.182           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.727           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.570           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.167           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.311           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.504           ms/op
ClientPb.getUser                        sample  242067   3.964 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.421           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.841           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.602           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.868           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.368           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.620           ms/op
ClientPb.listUser                       sample  204088   4.698 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.380           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.120           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.077           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.314           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.036           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.048           ms/op
