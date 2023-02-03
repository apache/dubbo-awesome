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
# Warmup Iteration   1: 0.970 ops/ms
# Warmup Iteration   2: 2.637 ops/ms
# Warmup Iteration   3: 5.535 ops/ms
Iteration   1: 5.712 ops/ms
Iteration   2: 5.547 ops/ms
Iteration   3: 5.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.593 ±(99.9%) 1.883 ops/ms [Average]
  (min, avg, max) = (5.521, 5.593, 5.712), stdev = 0.103
  CI (99.9%): [3.710, 7.477] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.755 ops/ms
# Warmup Iteration   2: 5.367 ops/ms
# Warmup Iteration   3: 5.961 ops/ms
Iteration   1: 5.911 ops/ms
Iteration   2: 6.042 ops/ms
Iteration   3: 6.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.985 ±(99.9%) 1.232 ops/ms [Average]
  (min, avg, max) = (5.911, 5.985, 6.042), stdev = 0.068
  CI (99.9%): [4.753, 7.218] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.670 ops/ms
# Warmup Iteration   2: 4.280 ops/ms
# Warmup Iteration   3: 5.900 ops/ms
Iteration   1: 5.432 ops/ms
Iteration   2: 5.644 ops/ms
Iteration   3: 5.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.492 ±(99.9%) 2.425 ops/ms [Average]
  (min, avg, max) = (5.399, 5.492, 5.644), stdev = 0.133
  CI (99.9%): [3.067, 7.917] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.691 ops/ms
# Warmup Iteration   2: 4.337 ops/ms
# Warmup Iteration   3: 4.966 ops/ms
Iteration   1: 4.695 ops/ms
Iteration   2: 4.664 ops/ms
Iteration   3: 4.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.710 ±(99.9%) 1.004 ops/ms [Average]
  (min, avg, max) = (4.664, 4.710, 4.771), stdev = 0.055
  CI (99.9%): [3.706, 5.714] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.959 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.790 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.074 ±(99.9%) 0.012 ms/op
Iteration   1: 6.055 ±(99.9%) 0.013 ms/op
Iteration   2: 5.794 ±(99.9%) 0.015 ms/op
Iteration   3: 5.278 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.709 ±(99.9%) 7.212 ms/op [Average]
  (min, avg, max) = (5.278, 5.709, 6.055), stdev = 0.395
  CI (99.9%): [≈ 0, 12.921] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.753 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.879 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.710 ±(99.9%) 0.011 ms/op
Iteration   1: 5.562 ±(99.9%) 0.013 ms/op
Iteration   2: 5.279 ±(99.9%) 0.014 ms/op
Iteration   3: 4.936 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.259 ±(99.9%) 5.723 ms/op [Average]
  (min, avg, max) = (4.936, 5.259, 5.562), stdev = 0.314
  CI (99.9%): [≈ 0, 10.982] (assumes normal distribution)


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
# Warmup Iteration   1: 15.864 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.301 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.073 ±(99.9%) 0.017 ms/op
Iteration   1: 5.715 ±(99.9%) 0.014 ms/op
Iteration   2: 5.601 ±(99.9%) 0.014 ms/op
Iteration   3: 5.234 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.516 ±(99.9%) 4.587 ms/op [Average]
  (min, avg, max) = (5.234, 5.516, 5.715), stdev = 0.251
  CI (99.9%): [0.930, 10.103] (assumes normal distribution)


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
# Warmup Iteration   1: 20.025 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 7.759 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.909 ±(99.9%) 0.014 ms/op
Iteration   1: 6.319 ±(99.9%) 0.012 ms/op
Iteration   2: 6.184 ±(99.9%) 0.017 ms/op
Iteration   3: 6.351 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.285 ±(99.9%) 1.611 ms/op [Average]
  (min, avg, max) = (6.184, 6.285, 6.351), stdev = 0.088
  CI (99.9%): [4.674, 7.895] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.445 ±(99.9%) 0.322 ms/op
# Warmup Iteration   2: 8.006 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.030 ±(99.9%) 0.026 ms/op
Iteration   1: 5.564 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.486 ms/op
                 createUser·p0.50:   5.308 ms/op
                 createUser·p0.90:   7.012 ms/op
                 createUser·p0.95:   7.782 ms/op
                 createUser·p0.99:   10.093 ms/op
                 createUser·p0.999:  26.623 ms/op
                 createUser·p0.9999: 35.815 ms/op
                 createUser·p1.00:   36.831 ms/op

Iteration   2: 5.485 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.404 ms/op
                 createUser·p0.50:   5.169 ms/op
                 createUser·p0.90:   7.021 ms/op
                 createUser·p0.95:   7.799 ms/op
                 createUser·p0.99:   9.976 ms/op
                 createUser·p0.999:  25.461 ms/op
                 createUser·p0.9999: 30.365 ms/op
                 createUser·p1.00:   31.490 ms/op

Iteration   3: 6.061 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.359 ms/op
                 createUser·p0.50:   5.767 ms/op
                 createUser·p0.90:   7.668 ms/op
                 createUser·p0.95:   8.454 ms/op
                 createUser·p0.99:   11.813 ms/op
                 createUser·p0.999:  17.341 ms/op
                 createUser·p0.9999: 31.546 ms/op
                 createUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168647
  mean =      5.693 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 58860 
    [ 5.000,  7.500) = 96294 
    [ 7.500, 10.000) = 11248 
    [10.000, 12.500) = 1431 
    [12.500, 15.000) = 422 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.359 ms/op
     p(50.0000) =      5.439 ms/op
     p(90.0000) =      7.258 ms/op
     p(95.0000) =      8.061 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     24.817 ms/op
     p(99.9900) =     34.141 ms/op
     p(99.9990) =     36.696 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.901 ±(99.9%) 0.252 ms/op
# Warmup Iteration   2: 6.648 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.369 ±(99.9%) 0.021 ms/op
Iteration   1: 5.305 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.130 ms/op
                 existUser·p0.50:   5.112 ms/op
                 existUser·p0.90:   6.636 ms/op
                 existUser·p0.95:   7.336 ms/op
                 existUser·p0.99:   9.896 ms/op
                 existUser·p0.999:  13.763 ms/op
                 existUser·p0.9999: 26.802 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   2: 5.693 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.982 ms/op
                 existUser·p0.50:   5.464 ms/op
                 existUser·p0.90:   7.201 ms/op
                 existUser·p0.95:   8.020 ms/op
                 existUser·p0.99:   10.913 ms/op
                 existUser·p0.999:  25.330 ms/op
                 existUser·p0.9999: 30.577 ms/op
                 existUser·p1.00:   31.785 ms/op

Iteration   3: 5.807 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.269 ms/op
                 existUser·p0.50:   5.636 ms/op
                 existUser·p0.90:   7.176 ms/op
                 existUser·p0.95:   7.913 ms/op
                 existUser·p0.99:   11.158 ms/op
                 existUser·p0.999:  28.470 ms/op
                 existUser·p0.9999: 34.209 ms/op
                 existUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 171531
  mean =      5.593 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 63345 
    [ 5.000,  7.500) = 97228 
    [ 7.500, 10.000) = 8635 
    [10.000, 12.500) = 1521 
    [12.500, 15.000) = 394 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.982 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      7.029 ms/op
     p(95.0000) =      7.799 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     22.986 ms/op
     p(99.9900) =     33.610 ms/op
     p(99.9990) =     35.361 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.331 ±(99.9%) 0.322 ms/op
# Warmup Iteration   2: 6.447 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.728 ±(99.9%) 0.022 ms/op
Iteration   1: 5.407 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.736 ms/op
                 getUser·p0.50:   5.145 ms/op
                 getUser·p0.90:   6.775 ms/op
                 getUser·p0.95:   7.561 ms/op
                 getUser·p0.99:   9.617 ms/op
                 getUser·p0.999:  25.946 ms/op
                 getUser·p0.9999: 28.647 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   2: 5.855 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.466 ms/op
                 getUser·p0.50:   5.579 ms/op
                 getUser·p0.90:   7.496 ms/op
                 getUser·p0.95:   8.348 ms/op
                 getUser·p0.99:   11.488 ms/op
                 getUser·p0.999:  16.488 ms/op
                 getUser·p0.9999: 29.797 ms/op
                 getUser·p1.00:   30.671 ms/op

Iteration   3: 5.874 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.954 ms/op
                 getUser·p0.50:   5.652 ms/op
                 getUser·p0.90:   7.283 ms/op
                 getUser·p0.95:   8.028 ms/op
                 getUser·p0.99:   10.338 ms/op
                 getUser·p0.999:  28.993 ms/op
                 getUser·p0.9999: 34.019 ms/op
                 getUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168399
  mean =      5.704 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 54690 
    [ 5.000,  7.500) = 100763 
    [ 7.500, 10.000) = 10937 
    [10.000, 12.500) = 1378 
    [12.500, 15.000) = 363 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.954 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      7.201 ms/op
     p(95.0000) =      8.053 ms/op
     p(99.0000) =     10.387 ms/op
     p(99.9000) =     22.774 ms/op
     p(99.9900) =     32.997 ms/op
     p(99.9990) =     35.803 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 17.752 ±(99.9%) 0.327 ms/op
# Warmup Iteration   2: 7.573 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.390 ±(99.9%) 0.024 ms/op
Iteration   1: 6.791 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   6.570 ms/op
                 listUser·p0.90:   8.233 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   12.550 ms/op
                 listUser·p0.999:  24.966 ms/op
                 listUser·p0.9999: 28.331 ms/op
                 listUser·p1.00:   30.310 ms/op

Iteration   2: 6.787 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.195 ms/op
                 listUser·p0.50:   6.463 ms/op
                 listUser·p0.90:   8.536 ms/op
                 listUser·p0.95:   9.585 ms/op
                 listUser·p0.99:   12.206 ms/op
                 listUser·p0.999:  28.732 ms/op
                 listUser·p0.9999: 32.974 ms/op
                 listUser·p1.00:   34.210 ms/op

Iteration   3: 6.749 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.609 ms/op
                 listUser·p0.50:   6.414 ms/op
                 listUser·p0.90:   8.421 ms/op
                 listUser·p0.95:   9.617 ms/op
                 listUser·p0.99:   11.816 ms/op
                 listUser·p0.999:  26.950 ms/op
                 listUser·p0.9999: 31.293 ms/op
                 listUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141639
  mean =      6.776 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 5462 
    [ 5.000,  7.500) = 108068 
    [ 7.500, 10.000) = 22959 
    [10.000, 12.500) = 3936 
    [12.500, 15.000) = 747 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.187 ms/op
     p(50.0000) =      6.488 ms/op
     p(90.0000) =      8.405 ms/op
     p(95.0000) =      9.503 ms/op
     p(99.0000) =     12.206 ms/op
     p(99.9000) =     26.929 ms/op
     p(99.9900) =     31.452 ms/op
     p(99.9990) =     34.128 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.593 ± 1.883  ops/ms
ClientPb.existUser                       thrpt       3   5.985 ± 1.232  ops/ms
ClientPb.getUser                         thrpt       3   5.492 ± 2.425  ops/ms
ClientPb.listUser                        thrpt       3   4.710 ± 1.004  ops/ms
ClientPb.createUser                       avgt       3   5.709 ± 7.212   ms/op
ClientPb.existUser                        avgt       3   5.259 ± 5.723   ms/op
ClientPb.getUser                          avgt       3   5.516 ± 4.587   ms/op
ClientPb.listUser                         avgt       3   6.285 ± 1.611   ms/op
ClientPb.createUser                     sample  168647   5.693 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.359           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.258           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.061           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.617           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.817           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.141           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.831           ms/op
ClientPb.existUser                      sample  171531   5.593 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.982           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.374           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.029           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.799           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.584           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.986           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.610           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.455           ms/op
ClientPb.getUser                        sample  168399   5.704 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.954           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.448           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.201           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.053           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.387           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.774           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.997           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.848           ms/op
ClientPb.listUser                       sample  141639   6.776 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.187           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.488           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.405           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.503           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.206           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.929           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.452           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.210           ms/op
