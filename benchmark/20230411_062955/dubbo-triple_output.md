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
# Warmup Iteration   1: 0.930 ops/ms
# Warmup Iteration   2: 2.502 ops/ms
# Warmup Iteration   3: 4.966 ops/ms
Iteration   1: 5.693 ops/ms
Iteration   2: 5.658 ops/ms
Iteration   3: 5.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.690 ±(99.9%) 0.570 ops/ms [Average]
  (min, avg, max) = (5.658, 5.690, 5.720), stdev = 0.031
  CI (99.9%): [5.121, 6.260] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.914 ops/ms
# Warmup Iteration   2: 5.007 ops/ms
# Warmup Iteration   3: 6.030 ops/ms
Iteration   1: 6.236 ops/ms
Iteration   2: 5.979 ops/ms
Iteration   3: 5.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.024 ±(99.9%) 3.527 ops/ms [Average]
  (min, avg, max) = (5.857, 6.024, 6.236), stdev = 0.193
  CI (99.9%): [2.497, 9.551] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.639 ops/ms
# Warmup Iteration   2: 4.748 ops/ms
# Warmup Iteration   3: 5.856 ops/ms
Iteration   1: 5.678 ops/ms
Iteration   2: 5.663 ops/ms
Iteration   3: 5.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.691 ±(99.9%) 0.655 ops/ms [Average]
  (min, avg, max) = (5.663, 5.691, 5.732), stdev = 0.036
  CI (99.9%): [5.036, 6.346] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.534 ops/ms
# Warmup Iteration   2: 4.238 ops/ms
# Warmup Iteration   3: 5.106 ops/ms
Iteration   1: 5.019 ops/ms
Iteration   2: 4.661 ops/ms
Iteration   3: 5.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.002 ±(99.9%) 6.056 ops/ms [Average]
  (min, avg, max) = (4.661, 5.002, 5.325), stdev = 0.332
  CI (99.9%): [≈ 0, 11.058] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 17.836 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.024 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.043 ±(99.9%) 0.009 ms/op
Iteration   1: 5.816 ±(99.9%) 0.009 ms/op
Iteration   2: 5.603 ±(99.9%) 0.014 ms/op
Iteration   3: 5.313 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.577 ±(99.9%) 4.606 ms/op [Average]
  (min, avg, max) = (5.313, 5.577, 5.816), stdev = 0.252
  CI (99.9%): [0.972, 10.183] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 15.783 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.142 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.493 ±(99.9%) 0.009 ms/op
Iteration   1: 5.555 ±(99.9%) 0.008 ms/op
Iteration   2: 5.031 ±(99.9%) 0.007 ms/op
Iteration   3: 4.912 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.166 ±(99.9%) 6.241 ms/op [Average]
  (min, avg, max) = (4.912, 5.166, 5.555), stdev = 0.342
  CI (99.9%): [≈ 0, 11.407] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.329 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 6.476 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.891 ±(99.9%) 0.012 ms/op
Iteration   1: 5.447 ±(99.9%) 0.016 ms/op
Iteration   2: 5.259 ±(99.9%) 0.011 ms/op
Iteration   3: 5.234 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.313 ±(99.9%) 2.129 ms/op [Average]
  (min, avg, max) = (5.234, 5.313, 5.447), stdev = 0.117
  CI (99.9%): [3.185, 7.442] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.621 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 7.859 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.552 ±(99.9%) 0.017 ms/op
Iteration   1: 6.334 ±(99.9%) 0.013 ms/op
Iteration   2: 6.440 ±(99.9%) 0.017 ms/op
Iteration   3: 5.773 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.182 ±(99.9%) 6.540 ms/op [Average]
  (min, avg, max) = (5.773, 6.182, 6.440), stdev = 0.358
  CI (99.9%): [≈ 0, 12.722] (assumes normal distribution)


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
# Warmup Iteration   1: 16.886 ±(99.9%) 0.271 ms/op
# Warmup Iteration   2: 7.229 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.020 ±(99.9%) 0.031 ms/op
Iteration   1: 5.322 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   4.932 ms/op
                 createUser·p0.90:   6.685 ms/op
                 createUser·p0.95:   8.012 ms/op
                 createUser·p0.99:   12.357 ms/op
                 createUser·p0.999:  23.101 ms/op
                 createUser·p0.9999: 31.588 ms/op
                 createUser·p1.00:   35.193 ms/op

Iteration   2: 5.528 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   5.276 ms/op
                 createUser·p0.90:   6.857 ms/op
                 createUser·p0.95:   7.512 ms/op
                 createUser·p0.99:   10.338 ms/op
                 createUser·p0.999:  23.434 ms/op
                 createUser·p0.9999: 29.046 ms/op
                 createUser·p1.00:   29.884 ms/op

Iteration   3: 5.103 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.572 ms/op
                 createUser·p0.50:   4.989 ms/op
                 createUser·p0.90:   5.759 ms/op
                 createUser·p0.95:   6.603 ms/op
                 createUser·p0.99:   9.781 ms/op
                 createUser·p0.999:  27.536 ms/op
                 createUser·p0.9999: 30.835 ms/op
                 createUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 180616
  mean =      5.312 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 87106 
    [ 5.000,  7.500) = 84829 
    [ 7.500, 10.000) = 5869 
    [10.000, 12.500) = 1649 
    [12.500, 15.000) = 588 
    [15.000, 17.500) = 305 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      6.554 ms/op
     p(95.0000) =      7.438 ms/op
     p(99.0000) =     11.040 ms/op
     p(99.9000) =     23.376 ms/op
     p(99.9900) =     31.054 ms/op
     p(99.9990) =     35.034 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 17.814 ±(99.9%) 0.259 ms/op
# Warmup Iteration   2: 6.565 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.235 ±(99.9%) 0.021 ms/op
Iteration   1: 5.010 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.159 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   6.103 ms/op
                 existUser·p0.95:   7.127 ms/op
                 existUser·p0.99:   10.125 ms/op
                 existUser·p0.999:  21.430 ms/op
                 existUser·p0.9999: 37.461 ms/op
                 existUser·p1.00:   38.076 ms/op

Iteration   2: 5.168 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.382 ms/op
                 existUser·p0.50:   4.858 ms/op
                 existUser·p0.90:   6.586 ms/op
                 existUser·p0.95:   7.356 ms/op
                 existUser·p0.99:   10.355 ms/op
                 existUser·p0.999:  24.458 ms/op
                 existUser·p0.9999: 28.338 ms/op
                 existUser·p1.00:   29.164 ms/op

Iteration   3: 5.231 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.208 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.234 ms/op
                 existUser·p0.95:   7.381 ms/op
                 existUser·p0.99:   11.207 ms/op
                 existUser·p0.999:  26.427 ms/op
                 existUser·p0.9999: 32.498 ms/op
                 existUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 186861
  mean =      5.134 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 109663 
    [ 5.000,  7.500) = 68775 
    [ 7.500, 10.000) = 6217 
    [10.000, 12.500) = 1276 
    [12.500, 15.000) = 406 
    [15.000, 17.500) = 234 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.382 ms/op
     p(50.0000) =      4.858 ms/op
     p(90.0000) =      6.332 ms/op
     p(95.0000) =      7.307 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     21.762 ms/op
     p(99.9900) =     35.865 ms/op
     p(99.9990) =     38.019 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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
# Warmup Iteration   1: 19.585 ±(99.9%) 0.337 ms/op
# Warmup Iteration   2: 6.923 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.583 ±(99.9%) 0.024 ms/op
Iteration   1: 5.110 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.130 ms/op
                 getUser·p0.50:   4.825 ms/op
                 getUser·p0.90:   6.087 ms/op
                 getUser·p0.95:   7.201 ms/op
                 getUser·p0.99:   10.895 ms/op
                 getUser·p0.999:  21.935 ms/op
                 getUser·p0.9999: 30.784 ms/op
                 getUser·p1.00:   34.079 ms/op

Iteration   2: 5.396 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.007 ms/op
                 getUser·p0.50:   5.063 ms/op
                 getUser·p0.90:   6.717 ms/op
                 getUser·p0.95:   7.873 ms/op
                 getUser·p0.99:   12.190 ms/op
                 getUser·p0.999:  24.271 ms/op
                 getUser·p0.9999: 28.740 ms/op
                 getUser·p1.00:   29.819 ms/op

Iteration   3: 5.917 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.075 ms/op
                 getUser·p0.50:   5.505 ms/op
                 getUser·p0.90:   8.061 ms/op
                 getUser·p0.95:   8.651 ms/op
                 getUser·p0.99:   11.087 ms/op
                 getUser·p0.999:  18.644 ms/op
                 getUser·p0.9999: 27.171 ms/op
                 getUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 175946
  mean =      5.454 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 78360 
    [ 5.000,  7.500) = 83692 
    [ 7.500, 10.000) = 10951 
    [10.000, 12.500) = 1721 
    [12.500, 15.000) = 747 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.007 ms/op
     p(50.0000) =      5.095 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      8.233 ms/op
     p(99.0000) =     11.289 ms/op
     p(99.9000) =     21.085 ms/op
     p(99.9900) =     28.600 ms/op
     p(99.9990) =     34.029 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 16.627 ±(99.9%) 0.294 ms/op
# Warmup Iteration   2: 7.768 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.512 ±(99.9%) 0.028 ms/op
Iteration   1: 6.241 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.818 ms/op
                 listUser·p0.50:   5.939 ms/op
                 listUser·p0.90:   7.340 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   12.222 ms/op
                 listUser·p0.999:  25.289 ms/op
                 listUser·p0.9999: 32.694 ms/op
                 listUser·p1.00:   33.128 ms/op

Iteration   2: 6.534 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.178 ms/op
                 listUser·p0.50:   6.242 ms/op
                 listUser·p0.90:   7.542 ms/op
                 listUser·p0.95:   8.782 ms/op
                 listUser·p0.99:   12.943 ms/op
                 listUser·p0.999:  28.740 ms/op
                 listUser·p0.9999: 32.492 ms/op
                 listUser·p1.00:   33.882 ms/op

Iteration   3: 6.681 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   6.341 ms/op
                 listUser·p0.90:   7.995 ms/op
                 listUser·p0.95:   9.224 ms/op
                 listUser·p0.99:   13.320 ms/op
                 listUser·p0.999:  24.951 ms/op
                 listUser·p0.9999: 29.100 ms/op
                 listUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148060
  mean =      6.480 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 5849 
    [ 5.000,  7.500) = 125714 
    [ 7.500, 10.000) = 12201 
    [10.000, 12.500) = 2575 
    [12.500, 15.000) = 829 
    [15.000, 17.500) = 377 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.404 ms/op
     p(50.0000) =      6.177 ms/op
     p(90.0000) =      7.643 ms/op
     p(95.0000) =      8.880 ms/op
     p(99.0000) =     12.993 ms/op
     p(99.9000) =     26.696 ms/op
     p(99.9900) =     32.093 ms/op
     p(99.9990) =     33.756 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.690 ± 0.570  ops/ms
ClientPb.existUser                       thrpt       3   6.024 ± 3.527  ops/ms
ClientPb.getUser                         thrpt       3   5.691 ± 0.655  ops/ms
ClientPb.listUser                        thrpt       3   5.002 ± 6.056  ops/ms
ClientPb.createUser                       avgt       3   5.577 ± 4.606   ms/op
ClientPb.existUser                        avgt       3   5.166 ± 6.241   ms/op
ClientPb.getUser                          avgt       3   5.313 ± 2.129   ms/op
ClientPb.listUser                         avgt       3   6.182 ± 6.540   ms/op
ClientPb.createUser                     sample  180616   5.312 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.403           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.030           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.554           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.438           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.040           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.376           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.054           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.193           ms/op
ClientPb.existUser                      sample  186861   5.134 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.382           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.858           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.332           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.307           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.600           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.762           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.865           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.076           ms/op
ClientPb.getUser                        sample  175946   5.454 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.007           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.095           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.955           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.233           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.289           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.085           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.600           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.079           ms/op
ClientPb.listUser                       sample  148060   6.480 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.404           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.177           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.643           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.880           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.993           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.696           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.093           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.882           ms/op
