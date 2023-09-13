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
# Warmup Iteration   1: 1.684 ops/ms
# Warmup Iteration   2: 4.144 ops/ms
# Warmup Iteration   3: 7.414 ops/ms
Iteration   1: 7.680 ops/ms
Iteration   2: 8.094 ops/ms
Iteration   3: 8.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.972 ±(99.9%) 4.641 ops/ms [Average]
  (min, avg, max) = (7.680, 7.972, 8.143), stdev = 0.254
  CI (99.9%): [3.332, 12.613] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.999 ops/ms
# Warmup Iteration   2: 6.862 ops/ms
# Warmup Iteration   3: 8.214 ops/ms
Iteration   1: 8.418 ops/ms
Iteration   2: 8.397 ops/ms
Iteration   3: 8.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.360 ±(99.9%) 1.495 ops/ms [Average]
  (min, avg, max) = (8.266, 8.360, 8.418), stdev = 0.082
  CI (99.9%): [6.865, 9.856] (assumes normal distribution)


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
# Warmup Iteration   1: 2.206 ops/ms
# Warmup Iteration   2: 6.890 ops/ms
# Warmup Iteration   3: 8.011 ops/ms
Iteration   1: 7.862 ops/ms
Iteration   2: 8.056 ops/ms
Iteration   3: 8.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.987 ±(99.9%) 1.979 ops/ms [Average]
  (min, avg, max) = (7.862, 7.987, 8.056), stdev = 0.108
  CI (99.9%): [6.008, 9.966] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.111 ops/ms
# Warmup Iteration   2: 5.800 ops/ms
# Warmup Iteration   3: 6.614 ops/ms
Iteration   1: 6.724 ops/ms
Iteration   2: 6.757 ops/ms
Iteration   3: 6.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.774 ±(99.9%) 1.099 ops/ms [Average]
  (min, avg, max) = (6.724, 6.774, 6.841), stdev = 0.060
  CI (99.9%): [5.675, 7.874] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.095 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.756 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.186 ±(99.9%) 0.009 ms/op
Iteration   1: 4.058 ±(99.9%) 0.010 ms/op
Iteration   2: 4.080 ±(99.9%) 0.011 ms/op
Iteration   3: 3.986 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.042 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (3.986, 4.042, 4.080), stdev = 0.049
  CI (99.9%): [3.145, 4.938] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.345 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.010 ms/op
Iteration   1: 3.974 ±(99.9%) 0.009 ms/op
Iteration   2: 3.887 ±(99.9%) 0.003 ms/op
Iteration   3: 3.914 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.925 ±(99.9%) 0.813 ms/op [Average]
  (min, avg, max) = (3.887, 3.925, 3.974), stdev = 0.045
  CI (99.9%): [3.112, 4.738] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.806 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.408 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.007 ms/op
Iteration   1: 4.019 ±(99.9%) 0.004 ms/op
Iteration   2: 4.026 ±(99.9%) 0.006 ms/op
Iteration   3: 3.947 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.997 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (3.947, 3.997, 4.026), stdev = 0.044
  CI (99.9%): [3.196, 4.798] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.004 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.779 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.016 ±(99.9%) 0.005 ms/op
Iteration   1: 4.875 ±(99.9%) 0.009 ms/op
Iteration   2: 4.806 ±(99.9%) 0.008 ms/op
Iteration   3: 4.628 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.770 ±(99.9%) 2.328 ms/op [Average]
  (min, avg, max) = (4.628, 4.770, 4.875), stdev = 0.128
  CI (99.9%): [2.441, 7.098] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.952 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 5.275 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.348 ±(99.9%) 0.018 ms/op
Iteration   1: 4.120 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.827 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.702 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  23.833 ms/op
                 createUser·p0.9999: 30.553 ms/op
                 createUser·p1.00:   31.719 ms/op

Iteration   2: 4.010 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.681 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   7.537 ms/op
                 createUser·p0.999:  14.205 ms/op
                 createUser·p0.9999: 28.447 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   3: 3.913 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.426 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.757 ms/op
                 createUser·p0.99:   7.193 ms/op
                 createUser·p0.999:  28.712 ms/op
                 createUser·p0.9999: 32.735 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239144
  mean =      4.013 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 453 
    [ 2.500,  5.000) = 224414 
    [ 5.000,  7.500) = 11511 
    [ 7.500, 10.000) = 1740 
    [10.000, 12.500) = 572 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      7.836 ms/op
     p(99.9000) =     22.895 ms/op
     p(99.9900) =     31.657 ms/op
     p(99.9990) =     33.700 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.856 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.745 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.012 ms/op
Iteration   1: 3.917 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.427 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   5.177 ms/op
                 existUser·p0.99:   8.045 ms/op
                 existUser·p0.999:  12.714 ms/op
                 existUser·p0.9999: 25.335 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   2: 3.894 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   5.046 ms/op
                 existUser·p0.99:   7.569 ms/op
                 existUser·p0.999:  24.601 ms/op
                 existUser·p0.9999: 26.863 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   3: 3.982 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.819 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.374 ms/op
                 existUser·p0.99:   7.627 ms/op
                 existUser·p0.999:  15.516 ms/op
                 existUser·p0.9999: 31.260 ms/op
                 existUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244091
  mean =      3.931 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 452 
    [ 2.500,  5.000) = 229487 
    [ 5.000,  7.500) = 10890 
    [ 7.500, 10.000) = 2402 
    [10.000, 12.500) = 472 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      7.823 ms/op
     p(99.9000) =     15.498 ms/op
     p(99.9900) =     29.838 ms/op
     p(99.9990) =     31.512 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.080 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.980 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.015 ms/op
Iteration   1: 4.196 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.542 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   6.218 ms/op
                 getUser·p0.99:   8.716 ms/op
                 getUser·p0.999:  15.647 ms/op
                 getUser·p0.9999: 27.321 ms/op
                 getUser·p1.00:   30.867 ms/op

Iteration   2: 4.050 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.698 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   5.709 ms/op
                 getUser·p0.99:   8.618 ms/op
                 getUser·p0.999:  25.984 ms/op
                 getUser·p0.9999: 29.370 ms/op
                 getUser·p1.00:   31.326 ms/op

Iteration   3: 4.041 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  12.337 ms/op
                 getUser·p0.9999: 31.657 ms/op
                 getUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234351
  mean =      4.094 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 117 
    [ 2.500,  5.000) = 214904 
    [ 5.000,  7.500) = 15506 
    [ 7.500, 10.000) = 2649 
    [10.000, 12.500) = 768 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 104 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     18.524 ms/op
     p(99.9900) =     30.591 ms/op
     p(99.9990) =     32.298 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 13.433 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 5.698 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.786 ±(99.9%) 0.018 ms/op
Iteration   1: 4.803 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   10.420 ms/op
                 listUser·p0.999:  26.182 ms/op
                 listUser·p0.9999: 29.884 ms/op
                 listUser·p1.00:   30.278 ms/op

Iteration   2: 4.791 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.586 ms/op
                 listUser·p0.99:   9.830 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 24.543 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   3: 4.921 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.658 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   7.070 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  16.812 ms/op
                 listUser·p0.9999: 19.056 ms/op
                 listUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198344
  mean =      4.838 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 159910 
    [ 5.000,  7.500) = 31120 
    [ 7.500, 10.000) = 5312 
    [10.000, 12.500) = 1251 
    [12.500, 15.000) = 281 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.802 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      6.545 ms/op
     p(99.0000) =     10.011 ms/op
     p(99.9000) =     20.403 ms/op
     p(99.9900) =     29.038 ms/op
     p(99.9990) =     30.245 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.972 ± 4.641  ops/ms
ClientPb.existUser                       thrpt       3   8.360 ± 1.495  ops/ms
ClientPb.getUser                         thrpt       3   7.987 ± 1.979  ops/ms
ClientPb.listUser                        thrpt       3   6.774 ± 1.099  ops/ms
ClientPb.createUser                       avgt       3   4.042 ± 0.896   ms/op
ClientPb.existUser                        avgt       3   3.925 ± 0.813   ms/op
ClientPb.getUser                          avgt       3   3.997 ± 0.801   ms/op
ClientPb.listUser                         avgt       3   4.770 ± 2.328   ms/op
ClientPb.createUser                     sample  239144   4.013 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.426           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.669           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.161           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.836           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.895           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.657           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.275           ms/op
ClientPb.existUser                      sample  244091   3.931 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.305           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.497           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.235           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.823           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.498           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.838           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.621           ms/op
ClientPb.getUser                        sample  234351   4.094 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.542           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.776           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.702           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.339           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.524           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.591           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.440           ms/op
ClientPb.listUser                       sample  198344   4.838 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.802           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.545           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.011           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.403           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.038           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.278           ms/op
