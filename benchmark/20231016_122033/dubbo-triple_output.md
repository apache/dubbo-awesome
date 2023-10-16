# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.990 ops/ms
# Warmup Iteration   2: 2.015 ops/ms
# Warmup Iteration   3: 4.357 ops/ms
Iteration   1: 4.877 ops/ms
Iteration   2: 5.221 ops/ms
Iteration   3: 5.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.120 ±(99.9%) 3.855 ops/ms [Average]
  (min, avg, max) = (4.877, 5.120, 5.262), stdev = 0.211
  CI (99.9%): [1.265, 8.975] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.430 ops/ms
# Warmup Iteration   2: 4.498 ops/ms
# Warmup Iteration   3: 5.482 ops/ms
Iteration   1: 5.706 ops/ms
Iteration   2: 5.612 ops/ms
Iteration   3: 5.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.644 ±(99.9%) 0.993 ops/ms [Average]
  (min, avg, max) = (5.612, 5.644, 5.706), stdev = 0.054
  CI (99.9%): [4.650, 6.637] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.288 ops/ms
# Warmup Iteration   2: 3.493 ops/ms
# Warmup Iteration   3: 4.860 ops/ms
Iteration   1: 5.203 ops/ms
Iteration   2: 5.289 ops/ms
Iteration   3: 5.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.169 ±(99.9%) 2.570 ops/ms [Average]
  (min, avg, max) = (5.014, 5.169, 5.289), stdev = 0.141
  CI (99.9%): [2.599, 7.738] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.309 ops/ms
# Warmup Iteration   2: 3.584 ops/ms
# Warmup Iteration   3: 4.450 ops/ms
Iteration   1: 4.525 ops/ms
Iteration   2: 4.637 ops/ms
Iteration   3: 4.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.564 ±(99.9%) 1.151 ops/ms [Average]
  (min, avg, max) = (4.525, 4.564, 4.637), stdev = 0.063
  CI (99.9%): [3.413, 5.714] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 21.933 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 7.865 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.274 ±(99.9%) 0.006 ms/op
Iteration   1: 6.215 ±(99.9%) 0.008 ms/op
Iteration   2: 6.161 ±(99.9%) 0.007 ms/op
Iteration   3: 5.947 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.108 ±(99.9%) 2.578 ms/op [Average]
  (min, avg, max) = (5.947, 6.108, 6.215), stdev = 0.141
  CI (99.9%): [3.530, 8.686] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 17.907 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 7.153 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.008 ±(99.9%) 0.012 ms/op
Iteration   1: 5.631 ±(99.9%) 0.015 ms/op
Iteration   2: 5.725 ±(99.9%) 0.008 ms/op
Iteration   3: 5.738 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.698 ±(99.9%) 1.066 ms/op [Average]
  (min, avg, max) = (5.631, 5.698, 5.738), stdev = 0.058
  CI (99.9%): [4.632, 6.764] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:41
# Fork: 1 of 1
# Warmup Iteration   1: 19.084 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 6.915 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.170 ±(99.9%) 0.011 ms/op
Iteration   1: 6.393 ±(99.9%) 0.011 ms/op
Iteration   2: 5.795 ±(99.9%) 0.012 ms/op
Iteration   3: 5.718 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.969 ±(99.9%) 6.744 ms/op [Average]
  (min, avg, max) = (5.718, 5.969, 6.393), stdev = 0.370
  CI (99.9%): [≈ 0, 12.713] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 21.614 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 8.400 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 7.131 ±(99.9%) 0.015 ms/op
Iteration   1: 6.945 ±(99.9%) 0.010 ms/op
Iteration   2: 6.841 ±(99.9%) 0.012 ms/op
Iteration   3: 7.033 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.939 ±(99.9%) 1.750 ms/op [Average]
  (min, avg, max) = (6.841, 6.939, 7.033), stdev = 0.096
  CI (99.9%): [5.189, 8.690] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.699 ±(99.9%) 0.355 ms/op
# Warmup Iteration   2: 8.039 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.202 ±(99.9%) 0.028 ms/op
Iteration   1: 5.994 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.788 ms/op
                 createUser·p0.50:   5.702 ms/op
                 createUser·p0.90:   7.397 ms/op
                 createUser·p0.95:   8.716 ms/op
                 createUser·p0.99:   12.657 ms/op
                 createUser·p0.999:  19.890 ms/op
                 createUser·p0.9999: 23.462 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   2: 5.861 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.372 ms/op
                 createUser·p0.50:   5.489 ms/op
                 createUser·p0.90:   7.414 ms/op
                 createUser·p0.95:   8.552 ms/op
                 createUser·p0.99:   11.305 ms/op
                 createUser·p0.999:  22.820 ms/op
                 createUser·p0.9999: 32.098 ms/op
                 createUser·p1.00:   33.194 ms/op

Iteration   3: 6.022 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   1.790 ms/op
                 createUser·p0.50:   5.718 ms/op
                 createUser·p0.90:   7.504 ms/op
                 createUser·p0.95:   8.845 ms/op
                 createUser·p0.99:   11.927 ms/op
                 createUser·p0.999:  27.099 ms/op
                 createUser·p0.9999: 31.671 ms/op
                 createUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 161039
  mean =      5.958 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 41500 
    [ 5.000,  7.500) = 104092 
    [ 7.500, 10.000) = 11370 
    [10.000, 12.500) = 2735 
    [12.500, 15.000) = 730 
    [15.000, 17.500) = 254 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.788 ms/op
     p(50.0000) =      5.628 ms/op
     p(90.0000) =      7.438 ms/op
     p(95.0000) =      8.716 ms/op
     p(99.0000) =     12.091 ms/op
     p(99.9000) =     22.871 ms/op
     p(99.9900) =     31.519 ms/op
     p(99.9990) =     35.896 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 17.479 ±(99.9%) 0.302 ms/op
# Warmup Iteration   2: 6.810 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.864 ±(99.9%) 0.026 ms/op
Iteration   1: 5.835 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.597 ms/op
                 existUser·p0.50:   5.472 ms/op
                 existUser·p0.90:   7.586 ms/op
                 existUser·p0.95:   8.536 ms/op
                 existUser·p0.99:   11.338 ms/op
                 existUser·p0.999:  19.698 ms/op
                 existUser·p0.9999: 31.293 ms/op
                 existUser·p1.00:   31.982 ms/op

Iteration   2: 5.907 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.154 ms/op
                 existUser·p0.50:   5.579 ms/op
                 existUser·p0.90:   7.463 ms/op
                 existUser·p0.95:   8.348 ms/op
                 existUser·p0.99:   11.518 ms/op
                 existUser·p0.999:  28.106 ms/op
                 existUser·p0.9999: 31.253 ms/op
                 existUser·p1.00:   31.654 ms/op

Iteration   3: 6.063 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   1.679 ms/op
                 existUser·p0.50:   5.710 ms/op
                 existUser·p0.90:   7.995 ms/op
                 existUser·p0.95:   9.060 ms/op
                 existUser·p0.99:   13.271 ms/op
                 existUser·p0.999:  30.843 ms/op
                 existUser·p0.9999: 40.495 ms/op
                 existUser·p1.00:   46.858 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 161655
  mean =      5.933 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 47897 
    [ 5.000, 10.000) = 110129 
    [10.000, 15.000) = 2983 
    [15.000, 20.000) = 412 
    [20.000, 25.000) = 42 
    [25.000, 30.000) = 100 
    [30.000, 35.000) = 60 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.679 ms/op
     p(50.0000) =      5.571 ms/op
     p(90.0000) =      7.700 ms/op
     p(95.0000) =      8.602 ms/op
     p(99.0000) =     12.321 ms/op
     p(99.9000) =     27.733 ms/op
     p(99.9900) =     38.339 ms/op
     p(99.9990) =     46.575 ms/op
     p(99.9999) =     46.858 ms/op
    p(100.0000) =     46.858 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 22.349 ±(99.9%) 0.410 ms/op
# Warmup Iteration   2: 8.762 ±(99.9%) 0.072 ms/op
# Warmup Iteration   3: 6.443 ±(99.9%) 0.033 ms/op
Iteration   1: 6.255 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.126 ms/op
                 getUser·p0.50:   5.816 ms/op
                 getUser·p0.90:   7.971 ms/op
                 getUser·p0.95:   9.722 ms/op
                 getUser·p0.99:   13.615 ms/op
                 getUser·p0.999:  25.068 ms/op
                 getUser·p0.9999: 38.535 ms/op
                 getUser·p1.00:   39.125 ms/op

Iteration   2: 6.032 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.154 ms/op
                 getUser·p0.50:   5.612 ms/op
                 getUser·p0.90:   7.610 ms/op
                 getUser·p0.95:   9.470 ms/op
                 getUser·p0.99:   12.976 ms/op
                 getUser·p0.999:  25.199 ms/op
                 getUser·p0.9999: 29.036 ms/op
                 getUser·p1.00:   30.671 ms/op

Iteration   3: 6.248 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.888 ms/op
                 getUser·p0.50:   5.906 ms/op
                 getUser·p0.90:   7.602 ms/op
                 getUser·p0.95:   8.913 ms/op
                 getUser·p0.99:   13.648 ms/op
                 getUser·p0.999:  27.294 ms/op
                 getUser·p0.9999: 31.203 ms/op
                 getUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 155334
  mean =      6.177 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 26994 
    [ 5.000,  7.500) = 110588 
    [ 7.500, 10.000) = 11583 
    [10.000, 12.500) = 4069 
    [12.500, 15.000) = 1186 
    [15.000, 17.500) = 416 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.126 ms/op
     p(50.0000) =      5.792 ms/op
     p(90.0000) =      7.733 ms/op
     p(95.0000) =      9.339 ms/op
     p(99.0000) =     13.451 ms/op
     p(99.9000) =     25.515 ms/op
     p(99.9900) =     37.648 ms/op
     p(99.9990) =     39.089 ms/op
     p(99.9999) =     39.125 ms/op
    p(100.0000) =     39.125 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 22.379 ±(99.9%) 0.376 ms/op
# Warmup Iteration   2: 8.578 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 7.323 ±(99.9%) 0.035 ms/op
Iteration   1: 6.991 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.810 ms/op
                 listUser·p0.50:   6.652 ms/op
                 listUser·p0.90:   8.585 ms/op
                 listUser·p0.95:   9.912 ms/op
                 listUser·p0.99:   13.091 ms/op
                 listUser·p0.999:  27.472 ms/op
                 listUser·p0.9999: 29.879 ms/op
                 listUser·p1.00:   30.081 ms/op

Iteration   2: 6.960 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.520 ms/op
                 listUser·p0.50:   6.554 ms/op
                 listUser·p0.90:   8.602 ms/op
                 listUser·p0.95:   10.371 ms/op
                 listUser·p0.99:   14.975 ms/op
                 listUser·p0.999:  27.548 ms/op
                 listUser·p0.9999: 30.556 ms/op
                 listUser·p1.00:   31.228 ms/op

Iteration   3: 7.007 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   2.564 ms/op
                 listUser·p0.50:   6.636 ms/op
                 listUser·p0.90:   8.503 ms/op
                 listUser·p0.95:   10.158 ms/op
                 listUser·p0.99:   13.531 ms/op
                 listUser·p0.999:  34.603 ms/op
                 listUser·p0.9999: 40.688 ms/op
                 listUser·p1.00:   41.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 137417
  mean =      6.986 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2695 
    [ 5.000, 10.000) = 127449 
    [10.000, 15.000) = 6200 
    [15.000, 20.000) = 710 
    [20.000, 25.000) = 81 
    [25.000, 30.000) = 181 
    [30.000, 35.000) = 60 
    [35.000, 40.000) = 34 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.520 ms/op
     p(50.0000) =      6.611 ms/op
     p(90.0000) =      8.569 ms/op
     p(95.0000) =     10.142 ms/op
     p(99.0000) =     14.270 ms/op
     p(99.9000) =     28.836 ms/op
     p(99.9900) =     38.749 ms/op
     p(99.9990) =     41.132 ms/op
     p(99.9999) =     41.157 ms/op
    p(100.0000) =     41.157 ms/op


# Run complete. Total time: 00:13:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.120 ± 3.855  ops/ms
ClientPb.existUser                       thrpt       3   5.644 ± 0.993  ops/ms
ClientPb.getUser                         thrpt       3   5.169 ± 2.570  ops/ms
ClientPb.listUser                        thrpt       3   4.564 ± 1.151  ops/ms
ClientPb.createUser                       avgt       3   6.108 ± 2.578   ms/op
ClientPb.existUser                        avgt       3   5.698 ± 1.066   ms/op
ClientPb.getUser                          avgt       3   5.969 ± 6.744   ms/op
ClientPb.listUser                         avgt       3   6.939 ± 1.750   ms/op
ClientPb.createUser                     sample  161039   5.958 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.788           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.628           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.438           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.716           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.091           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.871           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.519           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.176           ms/op
ClientPb.existUser                      sample  161655   5.933 ± 0.015   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.679           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.571           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.700           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.602           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.321           ms/op
ClientPb.existUser:existUser·p0.999     sample          27.733           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.339           ms/op
ClientPb.existUser:existUser·p1.00      sample          46.858           ms/op
ClientPb.getUser                        sample  155334   6.177 ± 0.016   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.126           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.792           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.733           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.339           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.451           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.515           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.648           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.125           ms/op
ClientPb.listUser                       sample  137417   6.986 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.520           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.611           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.569           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.142           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.270           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.836           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.749           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.157           ms/op
